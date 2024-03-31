# Lab-01  Part 8  การกำหนดรูปแบบพร้อมความกว้างของทศนิยมของอาร์กิวเมนต์

👉 แก้โปรแกรมตามรูปด้านล่างนี้
```csharp
const double i = 123.456789d;
Console.WriteLine("{0:F1}", i);
Console.WriteLine("{0:F2}", i);
Console.WriteLine("{0:F3}", i);
Console.WriteLine("{0:F4}", i);
Console.WriteLine("{0:F5}", i);
```
➢ รันโปรแกรมและบันทึกผล
<img width="960" alt="8" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/234f8433-3856-4b96-8b8d-d4c5acd57834">


## ❔ แบบฝึกหัด จงรันโปรแกรมและบันทึกภาพ output ของบรรทัดคำสั่งต่อไปนี้

``` csharp
1. string name = "Hello";
    Console.WriteLine(String.Format("{0} there. I said {0}! {0}???", name));
```

``` csharp
2. Console.WriteLine("{2:d} {0:d} {1:d}", 1, 2, 3);
```
<img width="908" alt="8 2" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/1d9ed988-aed3-46bf-8308-ae407e5d33d3">

``` csharp
3. Console.WriteLine("Hello " + "World");
```
<img width="897" alt="8 3" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/7704188c-ce24-4914-a6e6-450a6dea4b5f">

``` csharp
4. Console.WriteLine("Here comes a slash \\");
```
<img width="890" alt="8 4" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/743a6204-ef59-485b-9197-69231f555a60">

``` csharp
5. Console.WriteLine("|{0, 10}|", 999);
```
<img width="892" alt="8 5" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/d55e4d62-3b56-4448-ba18-4f747003f41b">

``` csharp
6. Console.WriteLine("|{0,-10}|", 000);
```
<img width="882" alt="8 6" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/304e3c99-3c4d-40fb-83ca-53dd0eab74ec">

``` csharp
7. Console.WriteLine("The value: {0}.", 500);
```
<img width="907" alt="8 7" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/bd4cb991-65fe-447e-919a-bfee4dbd1a24">

``` csharp
8. Console.WriteLine("The value: {0:C}.", 500);
```
<img width="914" alt="8 8" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/8a9a02b7-f1e7-4273-ab09-4b7963d20141">

``` csharp
9. Console.WriteLine("{0,-10:F4}", 12.3456789);
```
<img width="896" alt="8 9" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/b5a2ec04-b2ba-4461-b0c0-74fe2b376286">

``` csharp
10. Console.WriteLine("{0,-10:C}", 12.3456789);
```
<img width="907" alt="8 10" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/95e6591c-e2c2-4635-aef6-3d3ea9f3437e">

``` csharp
11. Console.WriteLine("{0,-10:E3}", 12.3456789);
```
<img width="942" alt="8 11" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/9348a9cc-00f3-4ae6-8195-8b672bddde5d">

``` csharp
12. Console.WriteLine("{0,-10:x}", 65535);  // (x = lower case)
```
<img width="926" alt="8 12" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/7bb1db04-3f0f-4ab2-8f62-a2468abeb96c">

``` csharp
13. Console.WriteLine("{0,-10:X}", 65535);  // (X = upper case)
```
<img width="886" alt="8 13" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/936fe2bb-3599-47eb-a41a-e316ea848ada">

``` csharp
14. int i;
    Console.WriteLine("Value\tSquared\tCubed");
    for(i = 1; i < 10; i++)
        Console.WriteLine("{0}\t{1}\t{2}", i, i*i, i*i*i);
```
<img width="927" alt="8 14" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/f9e2b5b4-ae8a-48b6-9280-4a15490e6fa3">

``` csharp
15. Console.WriteLine("{0:#.###}.", 1234.56789);
```
<img width="890" alt="8 15" src="https://github.com/NathaphonTan/03376836-OOP-2566-Lab-01/assets/144870609/07d1e819-69d6-4dad-810d-eaae14449e6f">


## [การใช้งานคำสั่ง Console.Read() และ Console.ReadLine()](./Lab-01-part-9-12.md)
