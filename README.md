<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Admin Page</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/7.0.1/css/all.min.css"
        integrity="sha512-2SwdPD6INVrV/lHTZbO2nodKhrnDdJK9/kg2XD1r9uGqPo1cUbujc+IYdlYdEErWNu69gVcYgdxlmVmzTWnetw=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link rel="stylesheet" href="style1.css">
</head>

<body>
    <aside class="sidebar">
        <h2 class="logo">Admin</h2><br>
        <nav class="menu">
            <a class="active" href="#">Dashboard</a><br>
            <a href="#">New orders</a><br>
            <a href="#">Assign orders</a><br>
            <a href="#">Inventory stock</a><br>

            <h2 class="second">Management</h2>
            <a href="#">Users</a><br>
            <a href="#">Drivers</a><br>
            <a href="#">Cylinders</a><br>
        </nav>
    </aside>

    <main class="main">
        <header class="topbar">
            <h1>Dashboard</h1>
            <div class="profile"></div>

        </header>

        <section class="cards">
            <div class="card">
                <h3>New orders</h3>
                <i class="fa-solid fa-bag-shopping"></i>
                <p>0</p>
            </div>

            <div class="card">
                <h3>Active Drivers</h3>
                <i class="fa-solid fa-store"></i>
                <p>2</p>
            </div>

            <div class="card">
                <h3>Total users</h3>
                <i class="fa-solid fa-users"></i>
                <p>20</p>
                <br>
            </div>

            <div class="card">
                <h3>Stock count</h3>
                <i class="fa-solid fa-calculator"></i>
                <p>0</p>
            </div>

        </section>

        <section class="secondsection">
            <div class="sec">
                <h1>Quick actions</h1>
                </div>
                </section>

                <div class="six-box-container">
                    <div class="six-box">Add Driver</div>
                    <div class="six-box">View Orders</div>
                    <div class="six-box">Assignments</div>

                    <div class="six-box">Refill Logistics</div>
                    <div class="six-box">Check Reports</div>
                    <div class="six-box">Manage Partners</div>
                </div>

</body>

</html>
