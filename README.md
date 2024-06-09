# CMS-Railway
!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Complain Management System</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        table,th,td{
            border:1px solid black;
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <h1>COMPLAIN MANAGEMENT SYSTEM</h1>
            <div class="user-info">
                <img src="user.png" alt="User Image" class="user-img">
                <button class="welcome-btn">Welcome User</button>
            </div>
        </header>
        <main>
            <div class="dashboard">
                <nav class="sidebar">
                    <ul>
                        <li><i class="icon">📥</i> <button on click="loadpage('inbox')">Inbox </button></li>
                        <li><i class="icon">📤</i> <button on click="loadPage('sent')"> Sent </button></li>
                        <li><i class="icon">➕</i> <button on click="loadPage('addUser')"> Add User </button></li>
                        <li><i class="icon">⚙</i>  <button on click="loadPage('activateUser')">Activate/Deactivate </button></li>
                        <li><i class="icon">📊</i> <button on click="loadpage('Rports')">Reports </button></li>
                    </ul>
                </nav>
             <!--
                <div class="content">
                    <div class="actions">
                        <button onclick="loadPage('inbox')">Load Inbox Page</button>
                        <button onclick="loadPage('sent')">Load Sent Page</button>
                        <button onclick="loadPage('addUser')">Load Add User Page</button>
                        <button onclick="loadPage('activateUser')">Load Activate/Deactivate Page</button>
                    </div>  
                -->
                    
                    <title>ALL COMPLAINT</title>
                    <TABLE BORDER="1" cellspacing="0" cellpadding="10">
                        <tr>
                            <td>Complain Id</td>
                            <td>Complain Desc</td>
                            <td>Division</td>
                            <td>Department</td>
                            <td>Website</td>
                            <td>Module</td>
                            <td>Employee Name</td>
                            <td>Status</td>
                            <td>Date</td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>
                        <tr>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                            <td></td>
                        </tr>

                    </TABLE>

                  
    
                    </div>
                </div>
            </main>
        </div>
        <script>
            function loadPage(page) {
                alert(Loading ${page} page...);
            }
        </script>
    </body>
    </html>
    
    
    <style> 
    
    body {
        font-family: Arial, sans-serif;
        background-color: #f4f4f4;
        margin: 0;
        padding: 0;
    }
    
    .container {
        width: 80%;
        margin: 0 auto;
        background-color: #fff;
        padding: 20px;
        box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }
    
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 10px 0;
        border-bottom: 1px solid #ddd;
    }
    
    h1 {
        margin: 0;
    }
    
    .user-info {
        display: flex;
        align-items: center;
    }
    
    .user-img {
        width: 50px;
        height: 50px;
        border-radius: 50%;
    }
    
    .welcome-btn {
        padding: 10px 20px;
        background-color: #5cb85c;
        color: white;
        border: none;
        cursor: pointer;
        margin-left: 10px;
    }
    
    .dashboard {
        display: flex;
        margin-top: 20px;
    }
    
    .sidebar {
        width: 20%;
        background-color: #f8f8f8;
        padding: 10px;
    }
    
    .sidebar ul {
        list-style: none;
        padding: 0;
    }
    
    .sidebar ul li {
        padding: 10px 0;
        border-bottom: 1px solid #ddd;
        display: flex;
        align-items: center;
    }
    
    .icon {
        margin-right: 10px;
    }
    
    .content {
        width: 80%;
        padding: 10px;
    }
    
    .actions {
        margin-bottom: 20px;
    }
    
    .actions button {
        display: block;
        margin-bottom: 10px;
        padding: 10px 20px;
        border: 1px solid #ddd;
        background-color: #f8f8f8;
        cursor: pointer;
    }
    
    .user-nav {
        display: flex;
        gap: 20px;
        margin-top: 10px;
    }
    
    .user-nav a {
        color: #007bff;
        text-decoration: none;
    }
    
    
    
    
    
    
    
    </style>
