---
description: >-
  อธิบายวิธีการสร้าง User Manual บน gitbook โดยทำงานร่วมกับ AI
  ซึ่งจะสามารถทำให้เราพัฒนาเอกสารได้เร็วขึ้นโดยการ Collaborate บน gitbook.
cover: .gitbook/assets/ginkgorian cover page.jpg
coverY: 0
---

# ☯ ใช้ AI ทำคู่มือ



{% hint style="info" %}
**ทำไมเราต้องเสียเวลาทำเรื่องนี้:** ถ้าใครสังเกตุทุกวันนี้มีการเปลี่ยนแปลงเกิดขึ้นหลายอย่างนั่นเป็นเพราะจำนวนผู้ใช้และความเร็วของ internet และ mobile device ที่สูงขึ้นทำให้นักพัฒนาต่างเร่งพัฒนา product ให้ออกสู่ตลาดได้ทันท่วงที ผู้ใช้เงก็มีการพัฒนาทักษะอยู่ตลอดเวลา แม้กระทั่งในเรื่องของ electronic file ที่เกี่ยวข้องกับการทำงานแทนกระดาษก็มีมาตรฐานต่างๆ ออกมาใหม่อยู่เรื่อย แล้วถ้าเราอยากมี Format เป็นของเราเองละ เป็นไปได้หรือไม่ ?
{% endhint %}

For **new team members**, สำหรับคนที่ยังใหม่กับการใช้งาน gitbook หรือ chatGPT สามารถทำความเข้าใจได้จากเอกสารนี้ ซึ่งจะรวบรวมเทคนิคที่จำเป็นต้องใช้ในการทำให้การแปลภาษาไทยเป็นภาษาอังกฤษเพื่อให้ภาษามีความสละสลวยขึ้น.

**Recommend accountability:** สมาชิกในทีมสามารถแก้ไขเอกสารร่วมกันได้พร้อมกันซึ่งจะทำให้การสร้างคู่มือการใช้งานหรือเอกสารอื่นๆที่มีวัตถุประสงค์คล้ายๆ กันได้

<table><thead><tr><th width="274.3333333333333">Contents</th><th width="237" align="center">Accountability</th><th align="center">Note</th></tr></thead><tbody><tr><td>Welcome to Product</td><td align="center">Product Owner</td><td align="center">Done</td></tr><tr><td>What we do</td><td align="center">C-Level</td><td align="center">Done</td></tr><tr><td>Our Features</td><td align="center">Marketing</td><td align="center"></td></tr><tr><td>Product Guides</td><td align="center">Product Owner</td><td align="center"></td></tr><tr><td>Fundamentals</td><td align="center">Product Owner</td><td align="center"></td></tr><tr><td>Getting Start</td><td align="center">Scrum</td><td align="center"></td></tr><tr><td>Document Management</td><td align="center">Scrum</td><td align="center"></td></tr><tr><td>Electronic Signature</td><td align="center">Scrum</td><td align="center"></td></tr><tr><td>Search</td><td align="center">Scrum</td><td align="center"></td></tr><tr><td>Delivering Content</td><td align="center">Scrum</td><td align="center"></td></tr><tr><td>Advanced Features</td><td align="center">Scrum</td><td align="center"></td></tr><tr><td>Troubleshooting and Support</td><td align="center">App Support</td><td align="center"></td></tr><tr><td><strong>USE Cases</strong></td><td align="center"></td><td align="center"></td></tr><tr><td>   For Designers</td><td align="center">TBC</td><td align="center"></td></tr><tr><td>   For Business</td><td align="center">Sale &#x26; MKT</td><td align="center"></td></tr><tr><td>   For Developers</td><td align="center">R &#x26; D</td><td align="center"></td></tr><tr><td>Product Tips</td><td align="center">Presale</td><td align="center"></td></tr></tbody></table>

<details>

<summary>เข้าใจโครงสร้างภาษาใน User Manual ?</summary>

* ให้ใช้สรรพนามเรียกผู้ใช้งานที่กำลังอ่านคู่มือว่า You.
* ให้เรียกผู้ส่งเอกสารให้ผู้อื่นลงนามว่า Sender.
* ให้เรียกผู้รับเอกสารเพื่อลงนามว่า Recipient(s).
* ให้เรียกลูกค้าที่เป็นสมาชิกแบบเสียเงินว่า Premium member หรือ Premium Subscriber.
* ให้เรียกลูกค้าที่เป็นสมาชิกแบบใช้ฟรีว่า Freemium member&#x20;



</details>

<details>

<summary>การใช้ chatGPT ช่วยสร้างข้อความ</summary>

การใช้ chatGPT ช่วยเขียนคู่มือการใช้งานเราจะต้องสร้างข้อความคำสั่งเป็นภาษอังกฤษที่ต้องชัดเจน กระชับ เช่น ให้เขียนอะไร เขียนให้ใครอ่านโดยอธิบายให้ชัดเจนถึงวัตถุประสงค์ที่คุณอยากได้ เช่น explain to customer what we do in software development to make our zDOX platform to reach our company vision that said "We believe people can work and live without paper."



Chat GPT ช่วยยกระดับการใช้ภาษาอังกฤษให้มีความสละสลวยมากขึ้นจนถึงระดับทางการคือ ChatGPT โดยทุกท่านสามารถนำภาษาอังกฤษที่ได้จากการแปลบน Google Translate มาให้แชท GPT ช่วยขัดเกลาประโยคนั้นๆ โดยพิมพ์ใน chat GPT และวางประโยคนั้นๆ ต่อท้าย

พิมพ์คำว่า Help improve this sentence ; วางประโยคภาษาอังกฤษที่แปลมาจาก GoogleTranslatet&#x20;

</details>

#### วีดีโอแสดงการใช้ chatGPT ช่วยเขียนคู่มือการใช้งาน

{% embed url="https://youtu.be/X3xRY-O4SeI" %}
Write "what we do" content with AL
{% endembed %}

{% embed url="https://youtu.be/JwS5DK5MkZw" %}
ChatGPT
{% endembed %}

<details>

<summary>การใช้ google translation แปลไทยเป็นอังกฤษ</summary>

สำหรับการใช้ Google translation ในการแปลให้ปรับประโยคภาษาไทยให้มีความกระชับก่อนแปล เช่น การตัดประธานของประโยคหรือคำในประโยคที่ใช้ฟุ่มเฟือยเพราะจะส่งผลให้รูปประโยคภาษาอังกฤษที่แปลจาก Google Translate นั้นมีความซับซ้อนและเข้าใจยากหรือสื่อความหมายผิดไม่ตรงตามบริบทในภาษาไทยที่ต้องการสื่อออกไป



</details>

<details>

<summary>การใช้งาน gitbook</summary>

สามารถอ่านรายละเอียดการใช้งาน gitbook เพิ่มเติมจาก [page gitbook](./#gitbook) ได้โดยตรงโดน Click ที่ [Link.](./#gitbook)

</details>

{% embed url="https://youtu.be/NfVtV73jK-M" %}
การใช้งาน gitbook EP1
{% endembed %}

{% embed url="https://youtu.be/jXm3fAvN2eg" %}
การใช้งาน gitbook EP2
{% endembed %}

{% embed url="https://youtu.be/Yx5oEHU2rUU" %}
การใช้งาน gitbook EP3
{% endembed %}

<details>

<summary>การทำงานร่วมกัน (Collaboration)</summary>



</details>

<details>

<summary>Version, Merge and Publish</summary>



</details>

<details>

<summary>Contributing</summary>

If you want to contribute changes, start a new change request and submit it for review. The People team will review it soon after.

</details>
