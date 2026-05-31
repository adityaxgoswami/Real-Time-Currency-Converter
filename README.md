# Real-Time-Currency-Converter
Built a real-time currency conversion application using live exchange rate APIs integrated with LLM tool binding to provide accurate conversions through natural language interactions.
# Real-Time Currency Converter using LLM Tool Binding

A real-time currency conversion application powered by Large Language Models (LLMs) and tool binding. The application fetches live exchange rates using external APIs and leverages LLM-driven tool calling to provide accurate currency conversions through natural language interactions.

---

## Features

* Real-time currency conversion using live exchange rate APIs
* Natural language query support using LLMs
* Tool binding / function calling for dynamic API interactions
* Supports multiple currencies worldwide
* Context-aware response generation
* Fast and interactive user experience

---

## Tech Stack

### Backend

* Python
* LLM Framework (LangChain / OpenAI / whichever you used)
* FastAPI (if used)

### APIs

* Real-Time Currency Exchange API

### AI / GenAI

* Tool Binding / Function Calling
* Large Language Models (LLMs)

---

## How It Works

1. User provides a query in natural language

Example:

```text
Convert 100 USD to INR
```

2. LLM identifies that external information is required

3. Tool binding triggers API calls to fetch live exchange rates

4. Conversion factor is retrieved

5. LLM generates a human-readable response

---

## Project Structure

```text
Currency-Converter/
│
├── app.py
├── requirements.txt
├── tools/
│   └── currency_tool.py
├── notebooks/
├── README.md
└── assets/
```

---

## Installation

Clone the repository:

```bash
git clone <your_repo_url>
cd Currency-Converter
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run:

```bash
python app.py
```

---

## Example Usage

Input:

```text
Convert 250 EUR into INR
```

Output:

```text
250 EUR ≈ 24,500 INR
```

---

## Future Improvements

* Support historical exchange rates
* Add voice-based queries
* Multi-language support
* Currency trend visualization
* Deploy as a web application

---

## Learning Outcomes

This project helped in understanding:

* Tool Calling / Tool Binding
* LLM Integration
* API Consumption
* Prompt Engineering
* Building GenAI Applications
* Real-Time Data Retrieval

---

## License

MIT License
