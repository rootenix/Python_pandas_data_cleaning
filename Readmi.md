<!-- A1-->

df=pd.read_csv('Info_HR.csv')
df.shape

bunda (60:1) natija chunki columlar ajratilmadi

Agar df=pd.read_csv('Info_HR.csv', sep=';') bo'lsa natija (60:11) chiqari
# sep('') aynan nima bilan ajratish kerak ekanligini bildiradi
<!-- A2-->

# df_small=pd.read_csv('Info_HR.csv', sep=';', usecols=['employee_id', 'first_name', 'department', 'salary','age'], nrows=10)

Bu yerda "secols" chiqishi kerak bo'lgan columlarni "nrows" esa lechta qator chiqish kerakligini belgilayapdi

<!--A3 -->

