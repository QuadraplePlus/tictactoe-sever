# tictactoe-sever

모바일 멀티플레이 틱텍토 게임 

# 서버 이용 방법

## 회원가입 (신규 유저 등록)
### 요청
>[POST] /users/signup

전달값 
<pre>
{
  'username':'honggildong'.
  'password':'hong1234',
  'name':'홍길동'
}
</pre>
### 결과

#### 성공
<pre>
{
  '_id':'1234567890abc',
  'username':'honggildong',
  'name':'홍길동'
}
</pre>
#### 실패
<pre>
{
  'message':'400 bad request'
}
</pre>
