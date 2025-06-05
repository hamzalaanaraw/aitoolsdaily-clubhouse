---
layout: base
title: Welcome to AI Tools Daily!
---

<div class="container">
    <h1 class="main-title">AI Tools Daily Clubhouse</h1>

    <div class="tools-grid">
        {% for tool in tools %}
        <div class="tool-card">
            <h2>{{ tool.name }}</h2>
            <p>{{ tool.description }}</p>
            <p><a href="{{ tool.url }}" target="_blank">Visit Site</a></p>
        </div>
        {% endfor %}
    </div>
</div>