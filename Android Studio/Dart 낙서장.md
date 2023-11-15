
dynamic 함수는 조심하게 써야하며 많이 사용하지 않음.


void main() {

  String? jiu = 'jiu'; //'null'을 사용하기 위해선 '?'를 붙여서
  jiu = null;          // 함수가 'null'이 될 수 있다는 것을
  if(jiu != null){     // 언어에게 알려줘야함
    jiu.isNotEmpty;

  }

}

  

// if(jiu != null){    
//     jiu.isNotEmpty;
//   }
//의 문장을 축약하면

  

void main() {

  String? jiu = 'jiu';
  jiu = null;
  jiu?.isNotEmpty;

}

변수를 수정할 수 없는 함수는 final 있음.
ex) 유저이름 같은 것 들.

late 는 초기 데이터 없이 변수를 선언 할 수 있음
그래서 late 앞에 var 또는 final 등이 올 수 잇음.
즉,  어떤 데이터가 올지 모른다고 말함.
하지만, 데이터를 넣기 전에는 사용X


API 작업을 할 때는 변수를 직접 적지 않을 수 있음.

'const' 변하지 않는 함 수.
ex) api_key 같은 것 들.

