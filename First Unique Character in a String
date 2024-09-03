class Solution {
    public int firstUniqChar(String s) {
        char[] strTochar = s.toCharArray();

        for (int i = 0; i < strTochar.length; i++) {
            for (int j = 0; j < strTochar.length; j++) {
                if (i != j && strTochar[i] == strTochar[j]) {
                    break;
                }

                if (j == strTochar.length - 1) {
                    return i;
                }
            }
        }

        return -1;
    }
}
