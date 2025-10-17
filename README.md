# codingTest
코테 공부

	1. int array sorting
		import java.util.*;
		Arrays.sort(int[])

	2. replaceAll("대상", "");

	3. String 배열로 변환
		char[] 변수 = String.toCharArray();

	4. String 대소문자 변환
		String.toLowerCase("String");
		String.toUpperCase("String");
		> if 조건문에 들어가면 대소문자체크도 가능

	5. 부분 문자열 찾는 메서드
		String.contains("찾을단어");

	6. 데이터타입 치환
		| 구분     		 | 변환 방향                           
		| -------- 		| --------------------------
		| 숫자 → 문자열	  | `숫자 + ""`
		| 문자열 → 숫자	  | `Integer.parseInt("123")`

	7. 문자열로 치환
		String 변수 = String.valueOf(치환할 변수);




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
