# my-online-store
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Professional Online Store</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header class="bg-dark text-white py-3">
        <div class="container">
            <div class="d-flex justify-content-between align-items-center">
                <h1 class="h3">My Professional Online Store</h1>
                <nav>
                    <ul class="nav">
                        <li class="nav-item"><a class="nav-link text-white" href="#home">Home</a></li>
                        <li class="nav-item"><a class="nav-link text-white" href="#products">Products</a></li>
                        <li class="nav-item"><a class="nav-link text-white" href="#contact">Contact</a></li>
                    </ul>
                </nav>
            </div>
        </div>
    </header>
    <main class="py-5">
        <section id="home" class="container mb-5">
            <div class="text-center">
                <h2>Welcome to My Online Store</h2>
                <p class="lead">Discover our amazing products!</p>
            </div>
        </section>
        <section id="products" class="container mb-5">
            <h2 class="text-center mb-4">Products</h2>
            <div class="row">
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/150" class="card-img-top" alt="Product 1">
                        <div class="card-body">
                            <h5 class="card-title">Product 1</h5>
                            <p class="card-text">Description of Product 1</p>
                            <p class="card-text">Price: $10.00</p>
                            <button class="btn btn-primary add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                </div>
                <div class="col-md-4 mb-4">
                    <div class="card">
                        <img src="https://via.placeholder.com/150" class="card-img-top" alt="Product 2">
                        <div class="card-body">
                            <h5 class="card-title">Product 2</h5>
                            <p class="card-text">Description of Product 2</p>
                            <p class="card-text">Price: $20.00</p>
                            <button class="btn btn-primary add-to-cart">Add to Cart</button>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section id="contact" class="container">
            <h2 class="text-center mb-4">Contact Us</h2>
            <form id="contact-form" class="mx-auto" style="max-width: 600px;">
                <div class="mb-3">
                    <label for="name" class="form-label">Name</label>
                    <input type="text" class="form-control" id="name" name="name" required>
                </div>
                <div class="mb-3">
                    <label for="email" class="form-label">Email</label>
                    <input type="email" class="form-control" id="email" name="email" required>
                </div>
                <div class="mb-3">
                    <label for="message" class="form-label">Message</label>
                    <textarea class="form-control" id="message" name="message" rows="4" required></textarea>
                </div>
                <button type="submit" class="btn btn-primary">Send</button>
            </form>
        </section>
    </main>
    <footer class="bg-dark text-white py-3">
        <div class="container text-center">
            <p>&copy; 2024 My Professional Online Store</p>
        </div>
    </footer>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
    <script src="scripts.js"></script>
</body>
</html>
