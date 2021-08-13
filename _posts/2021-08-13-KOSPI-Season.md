---
layout: single
title:  "월별 KOSPI 수익률 분석"
---
# 데이터 분석을 위한 pandas, 시각화를 위한 matplotlib, 주가 데이터 수집을 위한 FinanceDataReader
import pandas as pd
import matplotlib.pyplot as plt
import FinanceDataReader as fdr

# get KOSPI dataset (starts from 2015)
df = fdr.DataReader('KS11', '1980-01-01') # 코스피
df.shape

# 일별 시세 미리보기
df.head()
