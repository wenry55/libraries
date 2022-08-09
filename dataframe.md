## isna

```
df['swl'].isna()

ymdhm
2012-05-01 00:00    False
2012-05-01 00:10    False
2012-05-01 00:20    False
2012-05-01 00:30    False
2012-05-01 00:40    False
                    ...  
2022-07-18 23:10    False
2022-07-18 23:20    False
2022-07-18 23:30    False
2022-07-18 23:40    False
2022-07-18 23:50    False
Name: swl, Length: 276336, dtype: bool


df[['swl', 'tototf']].isna()

                  swl	  tototf
ymdhm		
2012-05-01 00:00	False	False
2012-05-01 00:10	False	False
2012-05-01 00:20	False	False
2012-05-01 00:30	False	False
2012-05-01 00:40	False	False
...	...	...
2022-07-18 23:10	False	False
2022-07-18 23:20	False	False
2022-07-18 23:30	False	False
2022-07-18 23:40	False	False
2022-07-18 23:50	False	False
276336 rows × 2 columns

df.isna().any(axis=1)
ymdhm
2012-05-01 00:00    False
2012-05-01 00:10    False
2012-05-01 00:20    False
2012-05-01 00:30    False
2012-05-01 00:40    False
                    ...  
2022-07-18 23:10    False
2022-07-18 23:20    False
2022-07-18 23:30    False
2022-07-18 23:40    False
2022-07-18 23:50    False
Length: 276336, dtype: bool
```
