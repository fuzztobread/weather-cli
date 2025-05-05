# 🌦️ Weather-Cli(Rust CLI App)

A simple and colorful command-line weather application written in Rust. It fetches current weather data for a city using the OpenWeatherMap API and displays it with colored formatting and emojis based on temperature.

---

## 🚀 Features

- Fetches current weather conditions using city and country code.
- Displays:
  - Weather description
  - Temperature (with emoji)
  - Humidity
  - Atmospheric pressure
  - Wind speed
- Colored output for different weather types.
- Environment-based API key loading for security.
- User-friendly prompts with looped interaction.

---

## 📦 Dependencies

- [`reqwest`](https://crates.io/crates/reqwest) – For HTTP requests
- [`serde`](https://crates.io/crates/serde) – For JSON deserialization
- [`colored`](https://crates.io/crates/colored) – For colorful terminal output
- [`dotenv`](https://crates.io/crates/dotenv) – For environment variable management

---

## 🛠️ Setup Instructions

1. **Clone the repository** (or create a new Rust project and paste the code):

   ```bash
   git clone https://github.com/your-username/weather-station-rust.git
   cd weather-station-rust
2. **Create a .env file in the root directory:
    ```bash
    WEATHER_API_KEY=your_api_key
3. **Add dependencies in Cargo.toml:
    ```bash
    [dependencies]
    reqwest = { version = "0.11", features = ["blocking", "json"] }
    serde = { version = "1.0", features = ["derive"] }
    colored = "2.0"
    dotenv = "0.15.0"
4. **Build and run the app:
    ```bash
    cargo run













