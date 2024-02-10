# study_data_analytics

## PANDAS
|구분|이름|설명|비고|
|--|--|--|--|
|1|[Series](./docs/pandas/01_pandas_series.ipynb)|pandas의 series에 대하여 이해하기||
|2|[DataFrame](./docs/pandas/02_pandas_DataFrame_iloc.ipynb)|pandas의 Dataframe에 대하여 이해하기||
|3-1|[Datetime](./docs/pandas/03_1_pandas_datetimes.ipynb)|날짜형 데이터 다루기||
|3-2|[Datetime(python)](./docs/pandas/03_1_pandas_datetimes.py)|날짜형 데이터 다루기(python)||
|5|[change Datetime](./docs/pandas/04_pandas_apply.py)|datetime 변환하기||
|5|[Datatype](./docs/pandas/05_pandas_TitanicFromDisaster_train.ipynb)|데이터 타입 이해하기<br/>데이터 타입 변환하기||
|6|[Pivot table](./docs/pandas/06_pandas_aggregations.ipynb)|pivot table 다루기||
|7|[Filtering](./docs/pandas/07_pandas_filtering_conditional.ipynb)|데이터 필터링 하기||
|8|[Preprocessing-missing values](./docs/pandas/08_pandas_preprocessing_missingvalues.ipynb)|결측치 전처리 하기||
|9|[Preprocessing-outlier](./docs/pandas/09_pandas_preprocessing_outlier.ipynb)|이상치 전처리 하기||
|10-1|[Data segmentation 1](./docs/pandas/10_1_pandas_usefuls.ipynb)|연속형 데이터를 범주형 데이터로 변환하기|.cut()|
|10-2|[Data segementation 2](10_2_pandas_usefuls./docs/pandas/.ipynb)|연속형 데이터를 범주형 데이터로 변환하기||
|11|[Data merge](./docs/pandas/10_pandas_merges.ipynb)|데이터 병합하기||

## VISUALIZATION
|구분|이름|설명|비고|
|--|--|--|--|
|1|[matplotlib](./docs/visualization/01_visualization_matplotlib_simple_korean.ipynb)|matplotlib 사용하여 시각화하기||
|2|[series visualization](./docs/visualization/02.visualization_univariate.ipynb)|단일변수 시각화하기|countplot : 막대그래프<br/>boxplot : 데이터 분포 확인과 이상값  찾기|
|3|[Data Frame visualization](./docs/visualization/03_visuallization_multivariate.ipynb)|다변수 시각화하기|barplot : 막대그래프<br/>boxplot : 데이터 분포 확인과 이상값 찾기<br/>scatterplot(산점도)<br/>lmplot : 산점도와 회귀선 같이 확인<br/>jointplot : 산점도와 히스토그램 같이 확인<br/>corr : 상관관계 수치로 확인<br/>pairplot : 상관관계 그래프로 확인<br/>lineplot : 선그래프|
|4|[visualization example](./docs/visualization/04_visualization_example.ipynb)|시각화 활용 예시||

## EDA
|구분|이름|설명|비고|
|--|--|--|--|
|1|[DDA & EDA example](docs/EDA/EDA_RentalCarOfContractType_together.ipynb)|DDA, EDA 과정 예시||

## CDA
|구분|이름|설명|비고|
|--|--|--|--|
|0|[CDA flowchart](https://app.diagrams.net/#G1RhsRvUFJK5r3qpLDKXI4z3ot9JtmnmSY)|CDA 순서도||
|1|[CDA : Categories](docs/CDA/01_CDA_RentalCarOfContractType_categories.ipynb)|x(범주형),y(범주형) 데이터 분석|카이제곱 검정(chi2_contingency) : 두 범주형 데이터의 독립성 증명|
|2|[CDA : Normality test](docs/CDA/02_CDA_RentalCarOfContractType_univariate.ipynb)|연속형 데이터의 정규성 검정|anderson normality test(anderson) : 레코드가 5000개 이상인 데이터의 정규성 검정 <br/>shapiro normality test(shapiro) : 레코드가 5천개 미만인 데이터의 정규성 검정|
|3|[CDA : continuous](docs/CDA/03_CDA_RentalCarOfContractType_continuous.ipynb)|x(연속형),y(연속형) 데이터 분석|피어슨 상관 분석(pearsonr): 둘 다 정규분포인 데이터들의 상관관계 분석<br/>서열상관분석(spearman) : 하나 이상의 비정규분포를 포함한 데이터들의 상관관계 분석|
|4|[CDA : mixed datas with unnormal data](docs/CDA/04_CDA_RentalCarOfContractType_mixed_unNormal.ipynb)|x(범주형),y(연속형 : 비정규 분포) 데이터 분석|윌콕슨 검정(ranksums) : 2개의 집단으로 구성된 범주형 데이터와 비정규분포인 연속형 데이터의 상관관계 분석<br/>kruskal test(kruskal) : 3개 이상의 집단으로 구성된 범주형 데이터와 비정규분포인 연속형 데이터의 상관관계 분석|
|5|[CDA : mixed datas with normal data](docs/CDA/05_CDA_RentalCarOfContractType_mixed_Normal.ipynb)|x(범주형),y(연속형 : 정규 분포) 데이터 분석|levene test : 등분산 검증<br/>T-test(ttest_ind/equal_var = True) : 2개의 집단으로 구성된 범주형 데이터와 정규분포인 연속형 데이터가 등분산일 때 두 데이터의 상관관계 분석<br/>ANOVA test(f_oneway) : 3개 이상의 집단으로 구성된 범주형 데이터와 정규분포인 연속형 데이터가 등분산일 때 두 데이터의 상관관계 분석<br/>T-test(ttest_ind/equal_var = False) : 2개 이상의 집단으로 구성된 범주형 데이터와 정규분포인 연속형 데이터가 이분산일 때 두 데이터의 상관관계 분석<br/>Kruskal test(kruskal) : 3개 이상의 집단으로 구성된 범주형 데이터와 정규분포인 연속형 데이터가 이분산일 때 두 데이터의 상관관계 분석|



## QUEST
|구분|이름|설명|비고|
|--|--|--|--|
|PANDAS|[Titanic_dataset](./docs/quests/pandas/Titanic_dataset.ipynb)|데이터프레임의 정보 확인하기|.describe()<br/>.unique()<br/>.columns|
|PANDAS|[SpineSurgeryList](./docs/quests/pandas/SpineSurgeryList.ipynb)|연속형 데이터를 범주형 데이터로 변환하기|.astype()|
|VISUALIZATION|[multivariate_OrdersDeliveryList](./docs/quests/visualizations/multivariate_OrdersDeliveryList.ipynb)|데이터 타입에 적절한 함수 사용하여 시각화하기|.sort_values(by=data,ascending=True/False)<br/>.reset_index(inplace=True)|
|VISUALIZATION|[multivariate_OrdersDeliveryLists_quest](./docs/quests/visualizations/multivariate_OrdersDeliveryLists_quest.ipynb)|데이터 필터링 연습하기|.str.slice(2,10)<br/>.str.startswith('')|
|DDA|[dataset_datatypes](./docs/quests/DDA/dataset_datatypes.md)|데이터의 데이터 타입 분석하기||
|DDA|[extract_5](./docs/quests/DDA/extract_5.ipynb)|범주형 데이터 시각화하기||
|DDA|[SpineSurgeryList_datetime](./docs/quests/DDA/SpineSurgeryList_datetime.ipynb)|시간형 데이터 시각화하기||
|DDA|[SpineSurgeryList_apply](./docs/quests/DDA/SpineSurgeryList_apply.py)|시간형 데이터로 변환하기하여 새로운 column 만들기||
|EDAs|[preprocessing_titanic_train](./docs/quests/EDAs/preprocessing_titanic_train.ipynb)|전처리 연습하기||
|EDAs|[EDA_RentalCarOfContractType](./docs/quests/EDAs/EDA_RentalCarOfContractType.ipynb)|DDA & EDA 실습|이상치, 결측치 처리하기|
|EDAs|[EDA_ShoppingMallDeliveryWithDate](./docs/quests/EDAs/EDA_ShoppingMallDeliveryWithDate.ipynb)|DDA & EDA 실습|이상치, 결측치 처리하기 </br>연속형 데이터를 범주형 데이터로 변환하기|
|EDAs|[EDA_kaggle_air_quality_in_covid19](./docs/quests/EDAs/EDA_kaggle_air_quality_in_covid19.ipynb)|DDA & EDA 실습|이상치, 결측치 처리하기|
|CDAs|[CDA_categories](./docs/quests/CDAs/CDA_categories.ipynb)|범주형 데이터 검증하기||
|CDAs|[CDA_continuous](./docs/quests/CDAs/CDA_continuous.ipynb)|연속형 데이터 검증하기||
|CDAs|[CDA_mixed_unVar](./docs/quests/CDAs/CDA_mixed_unVar.ipynb)|비정규 분포인 연속형 데이터가 포함된 데이터 검증하기||
|CDAs|[CDA_mixed_unVar_second](./docs/quests/CDAs/CDA_mixed_unVar_second.ipynb)|비정규 분포인 연속형 데이터가 포함된 데이터 검증하기2||
