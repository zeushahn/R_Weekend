# R_Weekend

과정 : R 프로그램밍 입문
기간 : 2023-12-30 ~ 2024-02-03

문의 사항
kennysy@naver.com

# R과 VSCode를 연결해서 사용하는 법
1. R을 설치한다.
 	- https://cran.r-project.org/ 에서 arm version 설치

2. 터미널에서 다음의 작업을 한다.
	- R
	- install.packages("IRkernel")
	- IRkernel::installspec(name="r", displayname="R")
	- q()

3. VSCode를 실행하고
	- ipyb file을 하나 생성하고
	- Kernel을 선택한다. 
	- 선택시 Jupyter Kernel에서 선택한다.

 VSCode에는 Jupyter 관련 package가 기존에 설치 되어 있어야 한다.

 # Mac의 VSCode에서 R Code사용시 필요한 내용

    options(warn = -1)
    Sys.setlocale(category = "LC_ALL", locale = "ko_KR.UTF-8")

# 시각화시 필요한 코드
	 options(repr.plot.width=15, repr.plot.height=9) 	
	 par(family = "AppleGothic", bg='white')
