# Multiple php project in nginx in docker
ลองสร้าง project php หลายตัวใส่ใน nginx ใน docker

## Run the application
1. Clone Project
```bash
git clone git@github.com:jame3032002/learning-to-create-multiple-php-project-in-nginx.git
```

2. เข้าไปที่ project
```bash
cd learning-to-create-multiple-php-project-in-nginx
```

3. สั่ง Run ด้วยคำสั่ง
```bash
docker-compose up
```

4. เปิด Browser แล้วลองเข้า

http://localhost:8081 จะแสดงข้อความ "Project 1"

http://localhost:8082 จะแสดงข้อความ "Project 2"

## สามารถอ่านบทความเพิ่มเติมได้ที่
[ลองสร้าง project php หลายตัวใส่ใน nginx ใน docker](https://www.kajame.xyz/blog/how-to-create-docker-container-nginx-and-php-multiple-project)
