# Pet Service - By QuyenKOL
```bash
Videos và phần Demo của project trong Project-Media.
```
## 1. Phân chia công viêc:

| Họ tên - Tài khoản Github | MSSV | Công việc thực hiện |
| :---         |     :---:      |          ---: |
| Phan Đức Quyền -  ducquyen12312ew | 20225916     | Thiết kế biểu đồ trình tự cho hệ thống. Thiết kế giao diện hệ thống. Thiết kế phần backend. Tham gia test hệ thống.|
| Nguyễn Văn Hoàn - HoanxHoan   | 20225718       | Phân tích yêu cầu, phân tích nghiệp vụ cho hệ thống.
Thiết kế kiến trúc và Use Case.
Thiết kế biểu đồ hoạt động cho hệ thống.
Tham gia test hệ thống.|
| Nguyễn Thanh Tân - turoisme    | 20225923      | Thiết kế cơ sở dữ liệu
Làm các chức năng kiểm thử đơn vị
Tham gia test hệ thống.|
| Phan Hoàng Long - anybody1234    | 20225738       | Làm các chức năng kiểm thử đơn vị.
Phân tích yêu cầu, phân tích nghiệp vụ cho hệ thống.
Tham gia test hệ thống.|
## 1. Clone the repository
```bash
git clone git@github.com:ducquyen12312ew/PetService.git
```
Then, move to the directory:
```bash
cd PetService-main
```
## 2. Install requirements
- Download and install `Node.js` from the official website: [Node.js](https://nodejs.org/)
- Open terminal and run:
```bash
node -v
npm -v
npm install
```
- Then install `nodemon`:
```bash
npm install -g nodemon
```
- Download `MongoDB`: [MongoDB Compass](https://www.mongodb.com/try/download/community)
- Then copy the command into terminal to install `mongoose` to interact with MongoDB:
```bash
npm install mongoose
```
# Run the website
From the directory of the repository, run the following:
```bash
Go to the folder containing PetService
cd PetService
nodemon src/index.js
```
Once the above script executes successfully, the local server will be launched. Open the following link in your web browser to view the website:
```bash
localhost:5000
```
To close the server, press `control + C` on the terminal window. 
# Vet mode
You can open the vet site to view the database in a user-friendly GUI. Open the following link:
```bash
localhost:5000/admin-secret
```
Then, log in using vet account:
- Username: `vet`
- Password: `vet`
















