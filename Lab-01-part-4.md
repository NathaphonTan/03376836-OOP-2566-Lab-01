# Lab-01 Part 4 จำนวนของอาร์กิวเมนต์ในคำสั่ง Console.WriteLine()

โดยทั่วไป การพิมพ์ข้อความออกทาง console สามารถพิมพ์ข้อความได้ทั้งแบบตายตัวและเปลี่ยนแปลงได้โดยโปรแกรม หากเราต้องการพิมพ์แบบตายตัวก็อาจใช้คำสั่ง `Console.WriteLine` เขียนเรียงกันไปเรื่อยๆ 

👉 แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
Console.WriteLine("This is text 1.");
Console.WriteLine("This is text 2.");
Console.WriteLine("This is text 3.");
```

➢ รันโปรแกรมและบันทึกผล
<img width="887" alt="4" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/e397a7be-1997-4f5d-a3a4-4c4e4daeead3">


ถ้าหากต้องการให้แก้ไขค่าตัวแปรที่จะแสดงออกทาง console เราก็อาจจะใช้ป้ายกำกับสำหรับรับค่าออกไปแสดงที่ output เรียกว่า place holder

การนับลำดับ place holder จะเริ่มจากตัวแรกที่มีค่าเป็น 0

👉 แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
Console.WriteLine(" {0} and {1}", 3, 6);
```

➢ รันโปรแกรมและบันทึกผล

<img width="917" alt="4 1" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/e096a03c-36b1-47b5-9e53-858bbf3cde3e">

❔ ถ้ามีการใช้ตัวเลขใน { } ที่กระโดด เช่น {0} {2} {3} จะใช้งานได้หรือไม่ อย่างไร จงอธิบาย


👉แก้โปรแกรมตามรูปด้านล่างนี้

```csharp
Console.WriteLine("{1}, {0} and {1}", 3, 6);
```

➢ รันโปรแกรมและบันทึกผล

 <img width="928" alt="4 2" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/2e46b23b-23b9-4b11-8b1a-29d02d94197f">

## [5. การกำหนดความกว้างของอาร์กิวเมนต์](./Lab-01-part-5-7.md)
