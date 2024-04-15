- 👋 Hi, I’m @shukhrat1101
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

n=int(input('YULDUZCHALAR SONINI KIRIT'))
a='✯'
c='✯\t✯'
d='▮\t▮'
print("✵".center(n+1))
print(a.center(n+1))
for i in range(2,n+1,2):
    print((c.expandtabs(i).center(n+1)))
print(' '.join(a*(n//2+1)))
for i in range(2):
    print((d.expandtabs(4)).center(n+1))


####### ARCHA ########
n=int(input('YULDUZCHALAR SONI>>>>>>'))
a='♣'
b=1
d='▮'
print("✵".center(n))
for i in range(1,n+1,2):
    b=a*i
    print(b.center(n))
for i in range(2):
    print((d*5).center(n))
