# DokumentasiAPI
dokumentasi ini di buat untuk belajar mengenal API


//dari web sederhana yang di buat untuk mencoba API beserta response yang didapatkan , di gunakan dan diimplementasikan pada postman

berikut dari isi Body 
{
    "email" : "sample@example.com",
    "password" : "123adsfadf@"
}

hasil response yang diinginkan / output yang diinginkan

{
    "status": "success",
    "message": "Authentication berhasil ditambahkan",
    "data": {
        "accessToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjAwZWQ3ZTkyLWMxMWEtNDdiMy05NDkzLTJiMmM1MTQyNzk5ZiIsImNvbXBhbnlJZCI6IjZkODEzYzM2LTM4N2QtNGRhYy1iNzM0LTAwZWQ1Mzk1ZjY1ZiIsImlhdCI6MTY5NzIzNzM3Nn0.T6G7Bb0MZMByu-rDwQPT4Ov1IMUsMZapxU_w8puJHSY",
        "refreshToken": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjAwZWQ3ZTkyLWMxMWEtNDdiMy05NDkzLTJiMmM1MTQyNzk5ZiIsImNvbXBhbnlJZCI6IjZkODEzYzM2LTM4N2QtNGRhYy1iNzM0LTAwZWQ1Mzk1ZjY1ZiIsImlhdCI6MTY5NzIzNzM3Nn0.GT0LUIuaxyrBPPdAe5hq4wKPQXlWBVwJaD0v0duXI04",
        "user": {
            "id": "00ed7e92-c11a-47b3-9493-2b2c5142799f",
            "name": "nama Toko",
            "role": "admin",
            "email": "sample@example.com",
            "officeId": "b5dc15e9-5437-455c-9dfe-57a516c27141",
            "companyId": "6d813c36-387d-4dac-b734-00ed5395f65f",
            "company_name": "nama Toko"
        }
    }
}
