### 1. [200518~200613] 생체 광학 데이터 분석 AI 경진대회

1. 배경 

빛을 응용한 뇌 내 성분 검사는 피부 상처 없이 다양한 성분 정보를 알 수 있습니다.
이는 뇌 활동 연구를 위해 신경영상을 얻을 수 있는 방법으로, 바늘(전극)을 찔러 넣는 방법인 뇌전도 검사를 대체할 방안으로 각광 받고 있습니다.


2. 목표
신경영상 및 뇌 활동 검사를 위해 제공된 모의 시뮬레이션 데이터를 기반으로 하는 AI 알고리즘 개발

3. 주최/주관
- [코리아스타트업포럼(AI i-CON)](http://kstartupforum.org/)
- [데이콘](https://dacon.io/)
- [중소기업기술정보진흥원(TIPA)](https://www.tipa.or.kr/)

4. 참가자 대상
- 일반인, 학생 등 누구나

5. 참고문헌

[1] Wabnitz, Heidrun, et al. "A time-domain NIR brain imager applied in functional stimulation experiments." *European Conference on Biomedical Optics. Optical Society of America (2005)*

[2] Perrey, Stéphane. "Non-invasive NIR spectroscopy of human brain function during exercise." *Methods 45.4, 289-299 (2008)*

[3] Golovynskyi, Sergii, et al. "Optical windows for head tissues in near‐infrared and short‐wave infrared regions: Approaching transcranial light applications." *Journal of biophotonics 11.12, e201800141 (2018)*

</br>

※ 본 경진대회는 코리아스타트업포럼에서 운영하는 인공지능 분야 개방형 혁신 네트워크 i-CON(innovation – Communication Open Network) 사업의 일환으로 기획ㆍ운영함
</br>
</br>

**데이터 설명**</br></br>
▶해결해야 하는 문제</br>
광원, 측정 스펙트럼으로부터 뇌 내 성분 농도 산출
</br>
</br>

▶train.csv(10MB)
- id : 구분자
- rho : 측정 거리 (단위: mm)
- src : 광원 스펙트럼 (650 nm ~ 990 nm)
- dst : 측정 스펙트럼 (650 nm ~ 990 nm)
- hhb : 디옥시헤모글로빈 농도
- hbo2 : 옥시헤모글로빈 농도
- ca : 칼슘 농도
- na : 나트륨 농도

</br>
▶test.csv(10MB)
- id : 구분자
- rho : 측정 거리 (단위: mm)
- src : 광원 스펙트럼 (650 nm ~ 990 nm)
- dst : 측정 스펙트럼 (650 nm ~ 990 nm)

</br>
▶sample_submission.csv(1MB)
-  hhb : 디옥시헤모글로빈 농도
- hbo2 : 옥시헤모글로빈 농도
- ca : 칼슘 농도
- na : 나트륨 농도

- - -