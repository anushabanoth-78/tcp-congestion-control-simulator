<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TCP Congestion Control Simulator</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            line-height: 1.6;
            background-color: #f9f9f9;
        }
        h1, h2 {
            color: #2c3e50;
        }
        code {
            background: #eee;
            padding: 6px;
            display: block;
            margin: 10px 0;
            border-radius: 5px;
        }
        ul {
            margin-left: 20px;
        }
        .container {
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 0px 10px rgba(0,0,0,0.1);
        }
    </style>
</head>

<body>

<div class="container">

    <h1>TCP Congestion Control Simulator</h1>

    <p>
        This project is an interactive simulator designed to visualize 
        <b>TCP congestion control algorithms</b> such as Slow Start, 
        Congestion Avoidance, Fast Retransmit, and Fast Recovery.
    </p>

    <h2>🚀 Project Overview</h2>
    <p>
        The simulator helps users understand how TCP manages congestion 
        by dynamically adjusting the <b>congestion window (cwnd)</b> 
        based on packet delivery and loss.
    </p>

    <h2>✨ Features</h2>
    <ul>
        <li>Interactive input for <b>ssthresh</b></li>
        <li>Manual packet state selection (Delivered / Lost)</li>
        <li>Real-time visualization of packet transmission</li>
        <li>Implements:
            <ul>
                <li>Slow Start</li>
                <li>Congestion Avoidance</li>
                <li>Fast Retransmit</li>
                <li>Fast Recovery</li>
            </ul>
        </li>
    </ul>

    <h2>🛠 Technologies Used</h2>
    <ul>
        <li>JavaScript</li>
        <li>React.js</li>
        <li>HTML & CSS</li>
    </ul>

    <h2>▶️ Getting Started</h2>

    <p><b>1. Clone the repository:</b></p>
    <code>git clone https://github.com/anushabanoth-78/tcp-congestion-control-simulator.git</code>

    <p><b>2. Navigate to folder:</b></p>
    <code>cd tcp-congestion-control-simulator/tcp_congestion</code>

    <p><b>3. Install dependencies:</b></p>
    <code>npm install</code>

    <p><b>4. Run the project:</b></p>
    <code>npm start</code>

    <p><b>5. Open in browser:</b></p>
    <code>http://localhost:3000</code>

    <h2>📊 Output</h2>
    <ul>
        <li>Visualization of congestion window behavior</li>
        <li>Packet transmission tracking</li>
        <li>TCP response to packet loss</li>
    </ul>

    <h2>🎯 Learning Outcomes</h2>
    <ul>
        <li>Understanding TCP congestion control</li>
        <li>Difference between Slow Start and Congestion Avoidance</li>
        <li>Impact of packet loss</li>
    </ul>

    <h2>🔮 Future Improvements</h2>
    <ul>
        <li>Add graphical charts (cwnd vs time)</li>
        <li>Support TCP Reno, Tahoe</li>
        <li>Deploy using GitHub Pages</li>
    </ul>

    <h2>🙌 Acknowledgment</h2>
    <p>
        This project is developed for educational purposes to help students 
        understand TCP congestion control concepts.
    </p>

    <h2>📜 License</h2>
    <p>MIT License</p>

</div>

</body>
</html>
