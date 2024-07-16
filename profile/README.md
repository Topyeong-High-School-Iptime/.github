# 토평고등학교 프로그래밍 동아리 아이피타임

> 동아리 소개  
작성 필요



> 동아리 특징    
작성 필요



> 동아리 주요 활동  
작성 필요

- 작성할때 참고하면 좋은 링크(https://gist.github.com/ihoneymon/652be052a0727ad59601)

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

[![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2FTopyeong-High-School-Iptime&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=%EB%B0%A9%EB%AC%B8%EC%9E%90+%EC%88%98&edge_flat=true)](https://hits.seeyoufarm.com)
