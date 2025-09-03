---
description: >-
  คือ การส่งค่าจากในเมธอดกลับออกมา ซึ่งใน Ruby เมธอดจะส่งค่ากลับเพียง 1 ค่าเสมอ
  (คือ object หนึ่งตัว) ค่าที่ส่งกลับสามารถเป็น object ใดก็ได้ 
  (แม้จะไม่ได้เขียน return ก็จะส่งค่าของบรรทัดสุดท้ายอัตโนมัติ
---

# Returning a value from function

\*object คือ หน่วยข้อมูลที่เมธอดเรียกทำงานได้ ทุกอย่างใน Ruby เป็น object ทั้งตัวเลข (5), ข้อความ ("Hello"), Array (\[1,2,3]), nil (ย่อมาจาก NilClass หมายถึง ไม่มีค่า,ว่าง)

```ruby
def say_hello
  "Hello"   # คืนค่า "Hello"
end

def say_hi
  return "Hi"   # คืนค่า "Hi"
end

def show
  puts "Showing"  # พิมพ์ออก แต่คืนค่าเป็น nil
end

puts say_hello # output=> Hello
puts say_hi     # output=> Hi
puts show      # output=> Showing \n nil

```



\
