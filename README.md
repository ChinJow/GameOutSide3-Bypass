
# GaneOutSide3 Bypass

นี่เป็นเพียง จุดนิดๆ ของเกม ที่ทำให้สามารถไปยังจุดจบได้ภายใน 3 นาที




## วิธีใช้
- Download ตัว dll ไปวางทับในไฟล์ /GameOutSideGame_Data/Managed/

- เมื่อวางทับเสร็จให้ รัน gog-backend.exe และทำการเปิดเกม

- เมื่อเข้าเกมแล้วกดอะไรให้เสร็จไปที่ประตูแรกและทำการเปิด cmd พิมพ์ตามข้างล่างและ Enter
```cmd
  curl -X POST http://localhost:3000/answers -H "Content-Type: application/json" --data {\"password\":\"ChinJowBypass\"}
```

- เมื่อประตูแรกเปิดให้ ออกเกม แล้วเข้าใหม่ 

- เมื่อเข้าใหม่แล้วให้กด Load Save 

- จากนั้น ผู้พัฒนาเกมจะไม่เห็นความเจ็บปวดของเราแล้ว 😎

