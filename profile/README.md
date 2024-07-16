# 토평고등학교 프로그래밍 동아리 아이피타임

> 동아리 소개  


> 동아리 특징  


> 동아리 주요 활동


```python
class Iptime:

  def __init__(self, name):
    self.name = name
    self.members = []
    self.activities = []

  def add_member(self, member_name):
    self.members.append(member_name)
    print(f"{member_name}는 동아리에 가입했습니다..")

  def alumni(self, member_name):
    if member_name in self.members:
      self.members.remove(member_name)
      print(f"{member_name}는 졸업했습니다.")

  def add_activity(self, activity):
    self.activities.append(activity)
    print(f"{activity} 활동 수행.")

  def club_info(self):
    print("아이피타임 정보")
    print(f"동아리 인원수: {len(self.members)}")
    print(f"동아리 활동내역: {self.activities}")
``` 
