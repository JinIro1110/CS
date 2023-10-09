# MIPS Design Principles
### 1. Simplicity favors regularity
#### 간단해지기 위해서 같은 형태를 사용하는 것이 좋음
* Arithmetic Operation은 동일한 형태
* 고정된 명령어 크기
* 명령어 포맷의 small number
* Opcode는 항상 6bit
### 2. smaller is faster
#### 작(적)을수록 더 빠르다
* 적은 수의 register, 적은 수의 instruction set
* 제한된 addressing mode
### 3. make the common case fast
#### 자주 일어나는 일을 빠르게
### 4. Good design demands good compromise
#### 좋은 설계는 적당한 절충이 필요

# 연산(Operaion)

* Operand 3개가 적절함
* 3개 이상은 써야 한 번에 처리가 가능, 구조가 간단할수록 성능이 좋음(Simplicity favors regularity)
* Registers : Operand의 값 저장
* ALU(Arithmetic Logic Unit) : Operation 수행
* Control Unit : ALU, Register의 동작 제어

# 레지스터

|No|이름|용도|
|---|---|---|
|0|테스트2|테스트3|
|2~3|테스트2|테스트3|
|4~7|테스트2|테스트3|
|8~15|
|16~23|
|24~25|
|28|
|29|
|30|
|31|