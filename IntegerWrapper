public class IntegerMethodsExample {
    public static void main(String[] args) {
        // === 1. Constructors ===
        Integer i1 = new Integer(123); // Constructor with int
        Integer i2 = new Integer("456"); // Constructor with String
        System.out.println("Constructor int: " + i1); // 123
        System.out.println("Constructor String: " + i2); // 456

        // === 2. Factory Methods (valueOf) ===
        Integer i3 = Integer.valueOf(789); // valueOf(int)
        Integer i4 = Integer.valueOf("1010"); // valueOf(String)
        Integer i5 = Integer.valueOf("FF", 16); // valueOf(String, radix)
        System.out.println("valueOf(int): " + i3); // 789
        System.out.println("valueOf(String): " + i4); // 1010
        System.out.println("valueOf(String, radix 16): " + i5); // 255

        // === 3. Conversion to Primitive Types ===
        System.out.println("intValue(): " + i1.intValue()); // 123
        System.out.println("byteValue(): " + i1.byteValue()); // 123 (narrowed)
        System.out.println("shortValue(): " + i1.shortValue()); // 123
        System.out.println("longValue(): " + i1.longValue()); // 123
        System.out.println("floatValue(): " + i1.floatValue()); // 123.0
        System.out.println("doubleValue(): " + i1.doubleValue()); // 123.0

        // === 4. String Conversion and Parsing ===
        // Parsing methods
        System.out.println("parseInt(String): " + Integer.parseInt("123")); // 123
        System.out.println("parseInt(String, radix): " + Integer.parseInt("FF", 16)); // 255
        System.out.println("parseUnsignedInt(String): " + Integer.parseUnsignedInt("4294967295")); // -1 (unsigned)
        System.out.println("parseUnsignedInt(String, radix): " + Integer.parseUnsignedInt("FF", 16)); // 255

        // toString methods
        System.out.println("toString(): " + i1.toString()); // "123"
        System.out.println("toString(int): " + Integer.toString(123)); // "123"
        System.out.println("toString(int, radix): " + Integer.toString(255, 16)); // "ff"
        System.out.println("toUnsignedString(int): " + Integer.toUnsignedString(-1)); // "4294967295"
        System.out.println("toUnsignedString(int, radix): " + Integer.toUnsignedString(255, 16)); // "ff"

        // Specialized string conversions
        System.out.println("toBinaryString(int): " + Integer.toBinaryString(10)); // "1010"
        System.out.println("toOctalString(int): " + Integer.toOctalString(10)); // "12"
        System.out.println("toHexString(int): " + Integer.toHexString(255)); // "ff"

        // === 5. Comparison Methods ===
        System.out.println("compareTo(Integer): " + i1.compareTo(i2)); // -1 (123 < 456)
        System.out.println("compare(int, int): " + Integer.compare(10, 20)); // -1
        System.out.println("compareUnsigned(int, int): " + Integer.compareUnsigned(-1, 1)); // 1 (-1 as 4294967295)
        System.out.println("equals(Object): " + i1.equals(new Integer(123))); // true

        // === 6. Bit Manipulation Methods ===
        System.out.println("bitCount(int): " + Integer.bitCount(10)); // 2 (1010 has 2 ones)
        System.out.println("highestOneBit(int): " + Integer.highestOneBit(10)); // 8 (1000)
        System.out.println("lowestOneBit(int): " + Integer.lowestOneBit(10)); // 2 (0010)
        System.out.println("numberOfLeadingZeros(int): " + Integer.numberOfLeadingZeros(10)); // 29
        System.out.println("numberOfTrailingZeros(int): " + Integer.numberOfTrailingZeros(10)); // 1
        System.out.println("reverse(int): " + Integer.reverse(10)); // Reverses 1010 in 32-bit
        System.out.println("reverseBytes(int): " + Integer.toHexString(Integer.reverseBytes(0x12345678))); // "78563412"
        System.out.println("rotateLeft(int, distance): " + Integer.rotateLeft(10, 1)); // 20 (1010 -> 10100)
        System.out.println("rotateRight(int, distance): " + Integer.rotateRight(10, 1)); // 5 (1010 -> 0101)
        System.out.println("signum(int): " + Integer.signum(-10)); // -1

        // === 7. Arithmetic and Utility Methods ===
        System.out.println("max(int, int): " + Integer.max(10, 20)); // 20
        System.out.println("min(int, int): " + Integer.min(10, 20)); // 10
        System.out.println("toUnsignedLong(int): " + Integer.toUnsignedLong(-1)); // 4294967295
        System.out.println("divideUnsigned(int, int): " + Integer.divideUnsigned(-1, 2)); // 2147483647
        System.out.println("remainderUnsigned(int, int): " + Integer.remainderUnsigned(-1, 2)); // 1

        // === 8. Hash Code ===
        System.out.println("hashCode(): " + i1.hashCode()); // 123
        System.out.println("hashCode(int): " + Integer.hashCode(123)); // 123

        // === 9. Constants ===
        System.out.println("MAX_VALUE: " + Integer.MAX_VALUE); // 2147483647
        System.out.println("MIN_VALUE: " + Integer.MIN_VALUE); // -2147483648
        System.out.println("SIZE: " + Integer.SIZE); // 32 (bits)
        System.out.println("BYTES: " + Integer.BYTES); // 4 (bytes)
        System.out.println("TYPE: " + Integer.TYPE); // int
    }
}
