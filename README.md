# EXPORT_SETTING_LABFU
การตั้งค่าระบบเพื่อการส่งออกข้อมูล 43 แฟ้ม : LABFU

### # การตั้งค่าระบบเพื่อการส่งออกข้อมูล 43 แฟ้ม : LABFU
***
โปรแกรมที่เกี่ยวข้อง

* <img width="32" height="32" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/HOSxP%20PCU.png"> **HOSxP PCU (สีเขียว)**
	- version : 3.61.5.30 ขึ้นไป ++
	- Download : [HOSxP_PCU_Setup_3.61.5.30.exe](http://cloud2.hosxp.net/)
	- Description : สำหรับการบันทึกข้อมูลการรักษาพยาบาลทั่วไป บันทึกผล LAB มีเมนูที่เกี่ยวข้องกับระบบการส่งออก LABFU คือ การจับคู่รายการ LAB ต่างๆ,การ Update ผลแลปที่เมนู Lab link และ คลินิกพิเศษโรคเรื้อรัง ,การใช้ คำสั่ง SQL เพื่อเข้า emergency mode
* <img width="32" height="32" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/BMSHOSxPXE4CloudApplicationInstaller.png"> **BMSHOSxPXE4CloudApplicationInstaller**
	- version : 4.61.12.9 ขึ้นไป ++
	- Download : [BMSHOSxPXE4CloudApplicationInstaller](https://my.pcloud.com/publink/show?code=XZMQU17ZvmXi5nm0818TncMWdE5ob43agAX7) 
	- Description : สำหรับ Download โปรแกรม และทำการติดตั้ง อีก 2 โปรแกรมเพิ่มเติมคือ HOSxPXE PCU และ BMSHOSxPStandard43Export ผ่าน ระบบ Internet จาก บริษัทของ BMS
* <img width="32" height="32" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/HOSxPXE%20PCU.png"> **HOSxPXE PCU (สีฟ้า)**
	- version : Build 73 ขึ้นไป ++
	- Download : ผ่านโปรแกรม BMSHOSxPXE4CloudApplicationInstaller เท่านั้น
	- Description : สำหรับการจับคู่ รายการ LAB และ รหัส 7 หลักตามรายการมาตรฐาน 43 แฟ้ม 2.3 ปี 2561
* <img width="32" height="32" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/BMSHOSxPStandard43Export.png"> **BMSHOSxPStandard43Export (สีขาว)**
	- version : Build 26 ขึ้นไป ++
	- Download : ผ่านโปรแกรม BMSHOSxPXE4CloudApplicationInstaller เท่านั้น 
	- Description : สำหรับการปรับปรุงโครงสร้างฐานข้อมูลของ hosxp และ การส่งออกข้อมูล 43 แฟ้ม


----------

ขั้นตอนมีดังนี้

1. ทำการติดตั้งโปรแกรม ต่างๆ ให้ครบ
2. การใช้คำสั่ง SQL เพื่อ เข้าการใช้งาน emergency mode : ผ่านโปรแกรม HOSxP PCU (สีเขียว) <img width="16" height="16" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/HOSxP%20PCU.png">  
3. การปรับปรุงโครงสร้างระบบฐานข้อมูล : ผ่านโปรแกรม BMSHOSxPStandard43Export (สีขาว)   <img width="16" height="16" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/BMSHOSxPStandard43Export.png">  
4. การจับคู่รายการ Lab ที่มีอยู่ในระบบ(Lab Link) และ Update ผล Lab : ผ่านโปรแกรม HOSxP PCU (สีเขียว) <img width="16" height="16" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/HOSxP%20PCU.png"> 
5. การใส่รหัส 7 หลักมาตรฐาน : ผ่านโปรแกรม HOSxPXE PCU (สีฟ้า)   <img width="16" height="16" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/HOSxPXE%20PCU.png">
6. การประมวลผลและส่งออกข้อมูล 43 แฟ้ม : ผ่านโปรแกรม BMSHOSxPStandard43Export (สีขาว)   <img width="16" height="16" src="https://raw.githubusercontent.com/inforeportable/EXPORT_SETTING_LABFU/master/Pic/BMSHOSxPStandard43Export.png">

https://gist.github.com/DavidWells/7d2e0e1bc78f4ac59a123ddf8b74932d
