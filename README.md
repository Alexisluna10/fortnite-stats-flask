# Fortnite Stats Viewer - Flask App

This is a web application built using **Python (Flask)** that allows users to retrieve and view real-time statistics of Fortnite players by consuming the public **[Fortnite API](https://fortnite-api.com/)**. Users can search by Epic username and receive key stats like Battle Pass progress, level, total kills, win rate, time played, and wins across different game modes (Solo, Duo, Squad).

## Screenshots

### Home page
![Home Screenshot](https://i.imgur.com/pVN8T8C.png)

### Player statistics
![Stats Screenshot](https://i.imgur.com/yupPkMj.png)

---

## Technologies Used

- 🔹 Python 3
- 🔹 Flask (micro web framework)
- 🔹 HTML5
- 🔹 CSS3
- 🔹 Jinja2 templating
- 🔹 REST API (Fortnite API)

---

## How to Get an API Key

1. Go to: [https://dash.fortnite-api.com/](https://dash.fortnite-api.com/)
2. Log in with your Discord account
3. Create a developer account and copy your API key
4. Replace `"YOUR_API_KEY"` in `main.py` with your personal key

---

## Example of a Valid Player Name

```
Tfue
Ninja
Bugha
```

> If the username does not exist or has private stats, the API may return an error or empty response.

---
