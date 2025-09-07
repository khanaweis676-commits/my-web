hi frends 


    body {
      background: #f4f7fb;
      color: #333;
    }

    header {
      background: #1e293b;
      color: white;
      padding: 15px 50px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    header h1 {
      font-size: 24px;
    }

    nav ul {
      display: flex;
      list-style: none;
    }

    nav ul li {
      margin-left: 20px;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-weight: 500;
      transition: 0.3s;
    }

    nav ul li a:hover {
      color: #38bdf8;
    }

    /* Hero Section */
    .hero {
      height: 90vh;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      background: linear-gradient(to right, #0f172a, #1e3a8a);
      color: white;
      flex-direction: column;
      padding: 20px;
    }

    .hero h2 {
      font-size: 45px;
      margin-bottom: 15px;
    }

    .hero p {
      font-size: 18px;
      margin-bottom: 25px;
    }

    .btn {
      background: #38bdf8;
      color: white;
      padding: 12px 25px;
      border: none;
      border-radius: 8px;
      font-size: 16px;
      cursor: pointer;
      transition: 0.3s;
    }

    .btn:hover {
      background: #0284c7;
    }

    /* Card Section */
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 20px;
      padding: 50px;
    }

    .card {
      background: white;
      padding: 20px;
      border-radius: 12px;
      box-shadow: 0px 4px 12px rgba(0,0,0,0.1);
      transition: 0.3s;
    }

    .card:hover {
      transform: translateY(-5px);
    }

    .card h3 {
      margin-bottom: 10px;
      font-size: 22px;
    }

    footer {
      text-align: center;
      background: #1e293b;
      color: white;
      padding: 20px;
      margin-top: 30px;
    }
 
  <!-- Header -->
  

# my-web
