# seaborn2
tips dataset
b=sns.load_dataset("tips")
sns.relplot(x="total_bill",y="tip",data=b) #to plot scatter plot by default
![image](https://user-images.githubusercontent.com/77687280/118762070-342d0100-b893-11eb-840c-83d008360694.png)

b=sns.load_dataset("tips")
sns.relplot(x="total_bill",y="tip",kind="line",data=b) #to plot line graph
![image](https://user-images.githubusercontent.com/77687280/118762377-b6b5c080-b893-11eb-92b2-3cce844904da.png)

b=sns.load_dataset("tips")
sns.violinplot(x="smoker",y="tip",data=b) #to plot violin plot 
![image](https://user-images.githubusercontent.com/77687280/118764589-62144480-b897-11eb-9912-294c75c5ea8a.png)
