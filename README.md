a
plt.show()
```

<img width="565" height="432" alt="download" src="https://github.com/user-attachments/assets/d3b0facb-64a4-4ede-af48-1eb37f412654" />


```python
sm.qqplot(np.reciprocal(df["Moderate Negative Skew_1"]),line = '45')
plt.show()
```

<img width="601" height="432" alt="download" src="https://github.com/user-attachments/assets/324358dc-8ebe-484d-a9f6-47413a345238" />

```python
sm.qqplot(df["Highly Negative Skew_1"],line = '45')
plt.show()
```

<img width="565" height="432" alt="download" src="https://github.com/user-attachments/assets/2eadc7fa-e1c0-4007-b1c2-03726d05a36f" />

```python
sm.qqplot(np.abs(df["Highly Negative Skew_1"]),line = '45')
plt.show()
```

<img width="565" height="432" alt="download" src="https://github.com/user-attachments/assets/b56bda7b-50eb-488a-8dec-61e16e6e5acc" />

```python
sm.qqplot(np.log(df["Highly Negative Skew_1"]),line = '45')
plt.show()
```

<img width="565" height="434" alt="download" src="https://github.com/user-attachments/assets/d40d0617-f287-4149-9afd-5376ef030ec7" />


```python
sm.qqplot(np.sqrt(df["Moderate Negative Skew_1"]),line='45')
plt.show()
```

<img width="565" height="432" alt="download" src="https://github.com/user-attachments/assets/d3e948f0-6364-4767-ae48-ecae548694ed" />

```python
pd.concat([CC,new],axis = 1)
```

<img width="418" height="266" alt="image" src="https://github.com/user-attachments/assets/b5535ca2-d372-4b05-9741-b8adb4c6049c" />


# RESULT:

Thus, we have successfully performed Feature Encoding and Transformation process and saved the data to a file.
       
