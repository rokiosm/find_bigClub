# 프로젝트 데이터 처리 개요 (Project Data Processing Overview)

1. **원본 데이터셋 (Original Dataset)**  
   Kaggle에서 다운로드한 데이터를 기반으로, `origindata` 디렉토리에 저장함.  
   *(Downloaded from Kaggle and stored in the `origindata` directory.)*

2. **데이터 가공 (Data Processing)**  
   가공한 데이터들은 `dataset` 디렉토리에 저장됨.  
   *(Processed datasets are saved in the `dataset` directory.)*

3. **데이터 가공을 위한 주요 작업 파일 (Key Processing Notebooks)**  
   - Elo Rating 계산  
   - 경기장 크기 비교 (중복 시 큰 값을 선택)  
   - 선수 몸값 처리  
   총 3개의 Jupyter Notebook 파일로 작업 진행.  
   *(Data processing performed using 3 main notebooks: Elo-rating, Stadium capacity (choosing the larger if duplicates), Player market value.)*

4. **최종 데이터 정리 및 제작 (Final Data Compilation)**  
   데이터 정리 및 최종 제작은 `data_parsing` 디렉토리에서 수행됨.  
   *(Final data cleaning and compilation performed within the `data_parsing` directory.)*

5. **향후 계획 (Future Plans)**  
   현재 데이터에 약간의 오류 및 편차가 존재하므로,  
   이후 정확한 데이터를 확보하고 크롤링하여 다시 제작할 예정임.  
   *(Due to some current errors and deviations, plan to re-collect accurate data and rebuild via web crawling.)*
