---
description: >-
  อธิบายวิธีการสร้าง User Manual บน gitbook โดยทำงานร่วมกับ AI
  ซึ่งจะสามารถทำให้เราพัฒนาเอกสารได้เร็วขึ้นโดยการ Collaborate บน gitbook.
cover: .gitbook/assets/ginkgorian cover page.jpg
coverY: 0
---

# 👋 Create User Manual with AI

{% hint style="info" %}
**ทำไมเราต้องมาเสียเวลาทำเรื่องนี้ :** ถ้าใครสังเกตุดีๆ ช่วงนี้มีเทคโนโลยีที่เกิดขึ้นมาใหม่ๆ มากมายนั่นเพราะว่าการเติบโตของจำนวนผู้ใช้และความเร็วของ internet และ mobile device ที่สูงขึ้นทำให้นักพัฒนาต่างเร่งสร้างสินค้าและบริการเพื่อออกมารองรับกับการเติบโต แม้กระทั่งการใช้งานเอกสารเอง ที่มี Format ที่เกิดขึ้นมาใหม่ๆ อย่างต่อเนื่อง แล้วถ้าเราจะมี Format เป็นของเราเองละ ?&#x20;
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

การใช้ chatGPT ช่วยเขียนคู่มือการใช้งานเราจะต้องสร้างข้อความคำสั่งเป็นภาษอังกฤษที่ต้องชัดเจน กระชับ เช่น ให้เขียนอะไร เขียนให้ใครอ่านโดยอธิบายให้ชัดเจนถึงวัตถุประสงค์ที่คุณอยากได้ เช่น explain to customer what we do in software development to make our zDOX platform to reach our company vision that said "We believe people can work and live without paper." ก็จะได้ผลลัพธ์แบบที่แสดงใน VDO.

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
