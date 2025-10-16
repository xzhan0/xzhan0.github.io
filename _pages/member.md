---
layout: page
permalink: /members/
title: Members
description: 
nav: true
nav_order: 9
---


<title>Our Team</title>
<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
    }

    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        min-height: 100vh;
        display: flex;
        align-items: center;
        justify-content: center;
        padding: 40px 20px;
    }

    .container {
        width: 100%;
        max-width: 1200px;
    }

    h1 {
        text-align: center;
        color: white;
        font-size: 2.5em;
        margin-bottom: 60px;
        text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
    }

    .org-chart {
        display: flex;
        flex-direction: column;
        align-items: center;
        position: relative;
    }

    .member-card {
        background: white;
        border-radius: 20px;
        padding: 30px;
        box-shadow: 0 10px 30px rgba(0,0,0,0.3);
        text-align: center;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        position: relative;
        z-index: 100;
    }

    .member-card:hover {
        transform: translateY(-10px);
        box-shadow: 0 15px 40px rgba(0,0,0,0.4);
    }

    .leader-container {
        display: flex;
        flex-direction: column;
        align-items: center;
        margin-bottom: 0;
    }

    .leader {
        min-width: 280px;
    }

    .headshot {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        object-fit: cover;
        margin: 0 auto 20px;
        display: block;
        border: 4px solid #667eea;
        box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }

    .member-name {
        font-size: 1.8em;
        font-weight: bold;
        color: #333;
        margin-bottom: 10px;
    }

    .member-role {
        font-size: 1.1em;
        color: #667eea;
        font-weight: 600;
    }

    /* Connection lines container */
    .connections {
        width: 100%;
        height: 120px;
        position: relative;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    /* Vertical line from leader */
    .vertical-top {
        width: 3px;
        height: 70px;
        background: white;
        position: absolute;
        top: 0;
        left: 50%;
        transform: translateX(-50%);
    }

    /* Horizontal line */
    .horizontal {
        width: 400px;
        height: 3px;
        background: white;
        position: absolute;
        top: 70px;
        left: 50%;
        transform: translateX(-50%);
    }

    /* Vertical lines to members */
    .vertical-left {
        width: 3px;
        height: 50px;
        background: white;
        position: absolute;
        top: 70px;
        left: calc(50% - 200px);
    }

    .vertical-right {
        width: 3px;
        height: 50px;
        background: white;
        position: absolute;
        top: 70px;
        right: calc(50% - 200px);
    }

    .team-members {
        display: flex;
        gap: 160px;
        position: relative;
    }

    .team-members .member-card {
        min-width: 240px;
    }

    @media (max-width: 768px) {
        .team-members {
            flex-direction: column;
            gap: 80px;
        }

        .connections {
            display: none;
        }

        h1 {
            font-size: 2em;
        }

        .member-card {
            min-width: 200px;
        }
    }
</style>


<div class="container">
    <h1>Our Team</h1>
    <div class="org-chart">
        <div class="leader-container">
            <div class="member-card leader">
                <img src="../assets/img/prof_pic.jpg" class="headshot" alt="Me">
                <div class="member-name"><a href="https://xzhan0.github.io/" target="_blank">Xianyang Zhan</a></div>
                <div class="member-role">Leader</div>
            </div>
        </div>
        
        <div class="connections">
            <div class="vertical-top"></div>
            <div class="horizontal"></div>
            <div class="vertical-left"></div>
            <div class="vertical-right"></div>
        </div>
        
        <div class="team-members">
            <div class="member-card">
                <img src="../assets/img/Yummi0.jpg" class="headshot" alt="Yummi">
                <div class="member-name"><a href="https://xzhan0.github.io/yummi/" target="_blank">Yummi</a></div>
                <div class="member-role">Team Member</div>
            </div>
            
            <div class="member-card">
                <img src="../assets/img/supra1.jpg" class="headshot" alt="Supra">
                <div class="member-name"><a href="https://xzhan0.github.io/yummi/" target="_blank">Supra</a></div>
                <div class="member-role">Team Member</div>
            </div>
        </div>
    </div>
</div>
