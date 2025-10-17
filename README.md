# codingTest
코테 공부

	1. int array sorting
		import java.util.*;
		Arrays.sort(int[])

	2. replaceAll("대상", "");

	3. String 배열로 변환
		String.toCharArray();

	4. String 대소문자 변환
		Character.toLowerCase("String");
		Character.toUpperCase("String");
		> if 조건문에 들어가면 대소문자체크도 가능








*****tip
	--최대공약수 계산 (유클리드 호제법)
    getGCD(int a, int b) {
        while (b != 0) {
            int temp = a % b; --t = 2 / t = 0
            a = b;  -- a = 8 / a = 2
            b = temp; -- b =2 / b = 0
        }
        return a;
    }
