<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous" />
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.3.0/css/all.min.css"
        integrity="sha512-SzlrxWUlpfuzQ+pcUCosxcglQRNAq/DZjVsC0lE40xsADsfeQoEypE+enwcOiGjk/bSuGGKHEyjSoQ1zVisanQ=="
        crossorigin="anonymous">
    <title>Portfolio dela</title>
</head>

<style>
     body {
        display: flex;
        flex-direction: column;
        min-height: 100vh;
    }

    .container {
        margin-top: 5px;
        margin-bottom: 10px;
        flex: 1;
    }

        .jumbotron {
            padding-top: 2rem;
            background-color: #ffffffca;
            justify-content: center;
        }

        .mybtns {
            display: flex;
            flex-direction: row;
            align-items: center;
            justify-content: center;
            margin-top: 20px;

        }

        .mybtns > button {
            margin-right: 10px;
        }

        .footer {
            text-align: center;
            color: black;
            padding: 15px 0;
            background-color: rgb(0, 0, 0, 0.2);
        }
</style>

<body>
    <nav class="navbar navbar-expand-lg navbar-dark bg-secondary shadow">
        <div class="container">
            <a class="navbar-brand" href="#">My Portfolio</a>
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav"
                aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item"><a href="#home" class="nav-link active" aria-current="page">Home</a></li>
                    <li class="nav-item"><a href="#profile" class="nav-link">Profile</a></li>
                    <li class="nav-item"><a href="#project" class="nav-link">Project</a></li>
                    <li class="nav-item"><a href="#contact_us" class="nav-link">Contact Us</a></li>
                </ul>
            </div>
        </div>
    </nav>

    <div id="profile" class="jumbotron jumbotron-fluid">
        <div class="container">
            <img src="dela.jpg" class="img-fluid rounded-circle mx-auto d-block" width="150px" alt="Gambar Profil">
            <h1 class="display-4 text-center">Fritadila Shafira</h1>
            <p class="lead text-center">Saya Fritadila Shafira seorang Mahasiswa Jurusan Sistem Informasi 
                di Universitas Gunadarma. Saya seorang siswa yang bermotivasi tinggi, 
                bertanggung jawab dan komunikatif. Saya tertarik pada teknologi dan analisis data.</p>
        </div>
    </div>

    <section id="project" class="bg-white">
        <div class="container">
            <div class="col-mb-5 mx-auto">
            <h2 class="text-center mt-5">My Project</h2>
            <div class="row">
                <div class="col-md-4 mb-5">
                    <img class="img-fluid" src="registrasi-form.jpg" width="300px" alt="">
                    <h3 class="mb-4">Building webiste using HTML5 Workshop LEPKOM Gunadarma University</h3>
                    <a href="registrasi-form.jpg" class="btn btn-secondary" >View Project</a>
                </div>
                <div class="col-md-4 mb-5">
                    <img class="img-fluid" src="myskillsql.jpg" width="300px" alt="">
                    <h3 class="mb-3">MySkill Short Class SQL for Data Analysis</h3>
                    <a href="myskillsql.jpg" class="btn btn-secondary" >View Project</a>
                </div>
                <div class="col-md-4 mb-5">
                    <img class="img-fluid" src="myskillexcel.jpg" width="300px" alt="">
                    <h3 class="mb-3">Myskill Short Class Basic Microsoft Excel</h3>
                    <a  href="myskillexcel.jpg" class="btn btn-secondary">View Project</a>
                </div>
            </div>
        </div>
        </div>
    </section>

    <section id="contact_us" class="bg-light">
        
        <div class="container">
            <h2 class="text-center md-4">Contact Us</h2>
            <div class="row">
                <div class="col-mt-5 mx-auto">
                    <div class="form-floating">
                        <input type="text" class="form-control" placeholder="Masukkan Nama Anda">
                        <label for="name">Name</label>
                    </div>
                    <div class="form-floating">
                        <input type="number" class="form-control" placeholder="0895406334848">
                        <label for="phone">Phone</label>
                   </div>
                    <div class="form-floating">
                        <textarea class="form-control" placeholder="Leave a message here" id="floatingTextarea"></textarea>
                        <label for="floatingTextarea">Message</label>
                    </div>  
                      <div class="mybtns">
                        <button type="button" class="btn btn-dark"> Save</button>
                        <button type="button" class="btn btn-outline-dark">Close</button>
                      </div>
                
                   </div>
        </div>
    </section>

    <footer class="text-center text-white" style="background-color: #726c6c;">
        <div class="container pt-4">
            <section class="mb-4">
                <a class="btn btn-link btn-floating btn-lg text-dark m-1"
                    href="https://www.facebook.com/fritadila.shafira.98?mibextid=LQQJ4d" role="button"
                    data-mdb-ripple-color="dark">
                    <li class="fab fa-facebook-f"></li>
                </a>

                <a class="btn btn-link btn-floating btn-lg text-dark m-1" href="https://twitter.com/aksisadgirl"
                    role="button" data-mdb-ripple-color="dark">
                    <li class="fab fa-twitter"></li>
                </a>

                <a class="btn btn-link btn-floating btn-lg text-dark m-1"
                    href="https://www.instagram.com/delashafira_?igsh=cmgzZWxzcmN4NXI0&utm_source=qr" role="button"
                    data-mdb-ripple-color="dark">
                    <li class="fab fa-instagram"></li>
                </a>

                <a class="btn btn-link btn-floating btn-lg text-dark m-1"
                    href="https://www.linkedin.com/in/dela-shafira-607b5a289?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app "
                    role="button" data-mdb-ripple-color="dark"><li class="fab fa-linkedin"></li>
                </a>

                <a class="btn btn-link btn-floating btn-lg text-dark m-1" href="https://github.com/Fritadila"
                    role="button" data-mdb-ripple-color="dark">
                    <li class="fab fa-github"></li>
                </a>
            </section>
        </div>

        <footer class="footer">
            © 2020 Copyright: 
            <a class="text-dark"  href="https://mdbootstrap.com/"> MDBootstrap.com</a>
        </footer>
    </footer>
</body>
</html>
