package 이지우;

public class test {

	public static void main(String[] args) {
		// 2024년 3월 16일 코드 시작.
		// 이름:이지우
		// 컴파일하기 위해서는 run버튼을 누르던지, Ctrl+F11
		int a = 10;
		int b = 20;
		System.out.println(a+b);  // a+b의 결과값을 출력한다.
		System.out.println(b);    // b의 값을 출력한다.
		System.out.println(a+b);  // a+b의 결과값을 출력한다.
		System.out.println(b);    // b의 값을 출력한다.
		System.out.println(a+b);  // a+b의 결과값을 출력한다.
		System.out.println(b);    // b의 값을 출력한다.
		System.out.println(a+b);  // a+b의 결과값을 출력한다.
		System.out.println(b);    // b의 값을 출력한다.
		System.out.println(a+b);  // a+b의 결과값을 출력한다.
		System.out.println(b);    // b의 값을 출력한다.
		System.out.println(a+b);  // a+b의 결과값을 출력한다.
		System.out.println(b);    // b의 값을 출력한다.
		
		/*
		 type 변수명 = 값 ;

         int   a   = 10 ;  // 정수형 변수 a에 10을 저장한다

         변수명은 영문 + 숫자
         특수문자는 언더 바( _ )만 가능

         int : 정수형 / 변수 a를 선언

         a=10 >>>  우변에 있는 값을 좌변에 저장(=10의 값을 a에 저장), true라는 뜻이 아님!
         
         1bit -> 0,1
         2bits -> 00, 01,10,11 
		 8bits = 1byte
		 
		 
		 flout a = 243,785f / 콤마 기준으로 나누는건가..
		 
		 char(=2byte)  c = 'A' ;  // ASCII 코드표
		 
		 string d = 'abc'; 6byte
		             ㄴ 문자열
		
		 char e = '김'; (x)
		           ㄴ> ㄱㅣㅁ

		 string f = '김'
		
		 데이터의 최소단위는 byte
		 * bit가 아님!

		 부등호면 "true or false"로 나와야함
		 
		 
		 ------ 상수 -----
		 
		 Math.pow(2,7) = 2의 7승
		 Math.pow(2,1/2) = 1 => 다음장 설명★
		 
		 strimg a = "abc"+10; // 문자열+숫자 => 문자열숫자
		                      // a = "abc10"
		                       
		                     
		 ----- (중요) 변수의 형 변환 -----
		 
		 double a = 4.8; (double은 8 byte 차지)
         int b = a; (x) (8 byte에서 4 byte로 넘어가기때문에 불가)  // 중복해서 정의할 수는 없음!
         if) int b=5;
             a = b;
             a=b; (b가 5이지만 a에는 5.0으로 저장) => 암시적 형변환(implicit casting)
            
             받는 값이 주려는 값보다 크기가 커야함
             int c = (int)4.9
                      ㄴ 명시적 형변환(explict casting)
                      ㄴ 4로 저장됨!
                      
            
            float은 4 byte이지만 long(8 byte)을 저장할 수 있음!
            ch => ascii 코드값이 저장되어있음
            
            int ch = 66;
            chor ch2 = ch;
            char ch3 = (char)ch;  // 명시적 형변환
            System.out.println(ch3) 'B'
            
            형 변환할 때에는 작은 값에서 큰 값으로 넘어가는 건 괜찮지만,
            큰 값에서 작은 값으로 넘길 때 정보 오차가 발생함
            
            
            -------------
            
            double a = 5+2; // a = 7.0
            double b = 5-2; // b = 3.0
            double d = 5/2; // d = 2.0
            
            + , - , * 은 모두 정수가 나옴
            / 는 정수가 나오는 경우(자바)도 있고 실수가 나오는 경우도 있음(파이썬은 무조건 실수)
           ===> 다음장 설명에 해당하는 내용
           
            double e = 5.0/2; //  e = 2.5
            double g = (double)5/2; // g = 2.5
            ㄴ 더블이 5에 붙어있음, 즉 (double)5 = 5.0
            double h = (double)(5/2); // h = 2.0
            
            정/정 --- 정 => 몫
            a / b => a/b에서의 나머지
            
            float 유무에 따라 byte가 달라짐
       
           
          
          
            
         
            
            
           
           
         
		 
		*/
	}

}
