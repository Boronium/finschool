# (Fin school) School made by fin

This program is meant for study and made by a 12 years old kid.
Fell free to look at my teacher's teach: https://youtu.be/1egtTXUJ3-4


IF anyone wanted to study try study this channel: https://youtu.be/MEaEVF3ZWfE (8Hours and 38 minuets long) ---> Don't forget to Subscribe Best of luck by Fin

This version is't finished it yet since ti forberifly explains abour oop bu using Python + Socket Feel free to change anythong you pleased.Let's get this straight i felt very lazy too translate thai to English so please use the translator Thanks uwu. p.s. pls don't mind the character used in the process ->w<- also this is copied from uncle chat so the content might not matched the study.

### Setting up

เปิด CMD / Terminal

```python
pip install finschool
```

### How to use

[STEP 1]
- เปิด IDLE ขึ้นมาแล้วพิมพ์...

```python
from finschool import Student, Lambhorgini, SpecialStudent, Teacher
allstudent = []

teacher1 = Teacher('Ada lovelace')
teacher2 = Teacher('Bill Gates')
print(teacher1.students)

#Day 1
print('---Day1---')
st1 = Student('Albert','Einstein')
allstudent.append(st1)
teacher2.AddStudent(st1)
print(st1.fullname)


#Day2
print('----Day2-----')
st2 = Student('Steve','Jobs')
allstudent.append(st2)
teacher2.AddStudent(st2)
print(st2.fullname)

#Day3
print('---Day3---')
st1.Coding()
st2.Coding()

#Day4
print('---Day4---')
st1.ShowEXP()
st2.ShowEXP()

#Day5
print('-----Day5-----')

stp1 = SpecialStudent('Thomas','Edison','Hitler')
allstudent.append(stp1)
teacher1.AddStudent(stp1)
print(stp1.fullname)
print('ครูครับขอคะแนนฟรีสัก 20 คะแนนได้ไหม')
stp1.exp = 20 #แก้ไขค่าไนคลาสได้
stp1.ShowEXP()
stp1.Coding()


#Day6
print('----Day6----')
stp1.ShowEXP()
for i in range(4):
st1.Coding()
st2.Coding()
st1.ShowEXP()
st2.ShowEXP()

#Day7
print('----Day7----')
print('นักเรียนหบัยย้ายกันยังไงจ๋ะ?')
print(allstudent)
for st in allstudent:
print('ผม: {} กลับบ้านด้วย {} ครับ'.format(st.name,st.vehicle))
if isinstance(st,SpecialStudent):
st.vehicle.SelfDriving(st)

#Day 8
print('-------Day8--------')

teacher1.CheckStudent()
teacher2.CheckStudent()

print('two students exp', st1 + st2)
```

- หรือเปิด cmd / terminal แล้วพิมพ์

```python
python -m finschool
```

Made by; Fin
FB: -
YouTube: -
