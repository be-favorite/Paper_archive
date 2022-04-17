# My own paper archive
논문과 책, 웹사이트 등을 통해 공부한 모델들을 아카이브합니다.

참고 문헌과 스터디 노트, 그리고 가능하다면 재현가능한 코드 또는 재현가능한 간략한 튜토리얼을 함께 제공하고자 합니다.

## Time Series

### Regression (추론 모델링)

#### Spurious regression
- 나종화. R 응용 시계열분석. 자유아카데미. 2020.
- 여러 시계열로 회귀를 수행할 때, 꼭 주의해야 할 알아두어야할 사항
- 🔗 [스터디 노트](https://be-favorite.tistory.com/76?category=1019644)
- 🔗 [R 튜토리얼](https://be-favorite.github.io/Multiple_timeseries/CCF%20analysis%20and%20DLM/Tutorials_DLM.html): CCF 분석의 허구적 상관 확인 과정 참고

#### Regression with ARIMA errors
- 나종화. R 응용 시계열분석. 자유아카데미. 2020.
- 🔗 [스터디 노트](https://be-favorite.tistory.com/74?category=1019644)
- 🔗 [R 튜토리얼](https://be-favorite.github.io/Multiple_timeseries/CCF%20analysis%20and%20DLM/Tutorials_DLM.html)

#### Distributed lag model
- 나종화. R 응용 시계열분석. 자유아카데미. 2020.
- 🔗 [스터디 노트](https://be-favorite.tistory.com/75?category=1019644)

#### Distributed lag non-linear model
- Gasparrini, Antonio, Benedict Armstrong, and M.G. Kenward. “Distributed Lag Non-Linear Models.” Statistics in Medicine 29 (September 20, 2010): 2224–34. https://doi.org/10.1002/sim.3940.
- Gasparrini, Antonio. “Distributed Lag Linear and Non-Linear Models in R: The Package Dlnm.” Journal of Statistical Software 43 (July 1, 2011): 1–20. https://doi.org/10.18637/jss.v043.i08.
- 🔗 [스터디 노트](https://be-favorite.tistory.com/80)
- 🔗 [PPT](https://be-favorite.github.io/Presentation_archive/DLM%2C%20DLNM/Introduction_dlm%2Cdlnm.html#6)
- 🔗 [R 튜토리얼](https://be-favorite.github.io/Multiple_timeseries/DLNMs/Tutorials_DLNMs.html)

### Forecasting (예측 모델링)

#### Exponential Smoothing
- 나종화. R 응용 시계열분석. 자유아카데미. 2020.
- 🔗 [스터디 노트](https://be-favorite.tistory.com/62?category=928223)

#### ARIMA model
- 나종화. R 응용 시계열분석. 자유아카데미. 2020.
- 🔗 [스터디 노트](https://be-favorite.tistory.com/63?category=928223)

#### Prophet
- Taylor, Sean, and Benjamin Letham. Forecasting at Scale, 2017. https://doi.org/10.7287/peerj.preprints.3190v2.
- 🔗 [스터디 노트](https://be-favorite.tistory.com/64)
- 🔗 [R 튜토리얼](https://be-favorite.github.io/Tutorial_prophet/Report.html)

#### Hierarchical Time Series Forecasting
- Athanasopoulos, George, Roman A. Ahmed, and Rob J. Hyndman. “Hierarchical Forecasts for Australian Domestic Tourism.” International Journal of Forecasting 25, no. 1 (January 1, 2009): 146–66. https://doi.org/10.1016/j.ijforecast.2008.07.004.
- Athanasopoulos, George, Rob Hyndman, Roman Ahmed, and Han Lin Shang. “Optimal Combination Forecasts for Hierarchical.” Computational Statistics & Data Analysis 55 (September 1, 2011): 2579–89. https://doi.org/10.1016/j.csda.2011.03.006.
- Hyndman, Rob J, George Athanasopoulos, and Han Lin Shang. “Hts: An R Package for Forecasting Hierarchical or Grouped Time Series,” n.d., 12.
- 🔗 [스터디 노트](https://be-favorite.tistory.com/60?category=928223)
- 🔗 [R 튜토리얼](https://otexts.com/fpp3/hts.html)

### Other techniques

#### Intervention analysis (Interrupted Time Series)
- Slides. “Intervention Analysis.” Accessed April 17, 2022. https://slides.com/tonyg/intervention-analysis.
- 🔗 [참고 자료](ITS_source.pdf)
- 🔗 [스터디 노트](ITS_note.pdf)
- 🔗 [R 코드](ITS_rcode.R)
- 🔗 [R 코드: arimax() 튜토리얼](ITS_arimax()_rcode.R)

#### Dynamic Time Warping (DTW)
- Berndt, Donald J., and James Clifford. “Using Dynamic Time Warping to Find Patterns in Time Series.” In Proceedings of the 3rd International Conference on Knowledge Discovery and Data Mining, 359–70. AAAIWS’94. Seattle, WA: AAAI Press, 1994.
- 선행 또는 후행하는 시계열, 시차가 존재하나 유사한 패턴이 존재하는 두 시계열을 잡아낼 수 있게끔 해주는 비유사성 측도(거리 측도) 알고리즘
- DTW distance를 이용해 계층적 군집 분석 수행 가능
- 🔗 [스터디 노트](DTW_note.pdf)
- 🔗 [R 튜토리얼](DTW_tutorial.R)

#### Discrete Wavelet Transform (DWT)
- Graps, Amara. “An Introduction to Wavelets.” IEEE Comp. Sci. Engi. 2 (February 1, 1995): 50–61. https://doi.org/10.1109/99.388960.
- Li, Daoyuan, Tegawendé F. Bissyandé, Jacques Klein, and Y. L. Traon. “Time Series Classification with Discrete Wavelet Transformed Data: Insights from an Empirical Study.” In SEKE, 2016. https://doi.org/10.18293/SEKE2016-067.
- 시계열들을 데이터의 열로 나열하여 classification을 수행할 때, 효과적인 차원 감소 방법. 
- 일종의 시계열 Feature engineering 기법에 해당
- 🔗 [스터디 노트](DWT_note.pdf)
- 🔗 [R 튜토리얼](DWT_tutorial.R)
