# python_continue_break
发工资

money=10000
import random
jixiaofen=0
for num in range(1,21):
    jixiaofen=random.randint(1,10)
    if jixiaofen<5:
        print(f"员工{num},绩效分{jixiaofen},低于5,下一个")
        continue
    else:
        money-=1000
        print(f"香员工{num}发1k,还有{money}院")
        if money<=0:
            print("done next time")
            break
