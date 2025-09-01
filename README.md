# SixtyFour API Tutorial Notebooks

> **Comprehensive interactive tutorials for mastering the SixtyFour AI platform**

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/sixtyfour-ai/notebooks)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 🚀 Quick Start

Get started with SixtyFour's powerful AI-driven data enrichment platform through hands-on tutorials. Each notebook provides production-ready examples you can implement immediately.

### Prerequisites

- **SixtyFour API Key** - [Get yours here](https://app.sixtyfour.ai/login)
- **Python 3.8+** with `requests` library
- **Google Colab account** (recommended for interactive execution)

## 📚 Tutorial Notebooks

### Core Enrichment APIs

| Notebook | Description | Use Cases | Complexity |
|----------|-------------|-----------|------------|
| **[Company Enrichment](sixtyfour_enrich_company_tutorial.ipynb)** | Deep company research and data structuring | Lead qualification, market research, competitive analysis | ⭐⭐⭐ |
| **[Lead Enrichment](sixtyfour_enrich_lead_tutorial.ipynb)** | Individual prospect research and contact discovery | Sales prospecting, candidate sourcing, relationship mapping | ⭐⭐⭐ |

### Contact Discovery APIs

| Notebook | Description | Use Cases | Complexity |
|----------|-------------|-----------|------------|
| **[Email Finding](sixtyfour_find_email_tutorial.ipynb)** | Email discovery and validation techniques | Outbound sales, recruitment, marketing campaigns | ⭐⭐ |
| **[Phone Finding](sixtyfour_find_phone_tutorial.ipynb)** | Phone number discovery and formatting | Direct sales, customer support, lead qualification | ⭐⭐ |

### Intelligence & Analysis

| Notebook | Description | Use Cases | Complexity |
|----------|-------------|-----------|------------|
| **[QA Agent](sixtyfour_qa_agent_tutorial.ipynb)** | Autonomous data qualification and scoring | Data quality assessment, lead scoring, compliance checks | ⭐⭐⭐⭐ |

## 🎯 What You'll Learn

- **API Integration Patterns** - Production-ready implementation examples
- **Error Handling** - Robust error management and retry strategies  
- **Data Optimization** - Best practices for structuring requests and responses
- **Async Workflows** - Handling long-running enrichment jobs efficiently
- **Cost Optimization** - Techniques to maximize API efficiency and minimize costs

## 🛠️ Getting Started

### Option 1: Google Colab (Recommended)
1. Click any notebook link above
2. Select "Open in Colab" 
3. Add your SixtyFour API key when prompted
4. Run cells interactively

### Option 2: Local Development
```bash
# Clone the repository
git clone https://github.com/sixtyfour-ai/notebooks.git
cd notebooks

# Install dependencies
pip install requests python-dotenv jupyter

# Set up your API key
echo "SIXTYFOUR_API_KEY=your_api_key_here" > .env

# Launch Jupyter
jupyter notebook
```

## �� API Key Setup

1. **Sign up** at [app.sixtyfour.ai](https://app.sixtyfour.ai/login)
2. **Navigate** to your dashboard
3. **Generate** an API key under "Keys" → "Create new key"
4. **Copy** your key and use it in the notebooks

## 📖 Documentation & Resources

- **[API Documentation](https://docs.sixtyfour.ai)** - Complete API reference
- **[Developer Portal](https://app.sixtyfour.ai)** - Dashboard and key management
- **[Community Support](https://github.com/sixtyfour-ai/notebooks/discussions)** - Get help from other developers
- **[Status Page](https://status.sixtyfour.ai)** - API status and uptime monitoring

## 🏗️ Production Implementation

These notebooks are designed for production use. Key considerations:

### Performance
- **Rate Limiting** - Implement exponential backoff for API calls
- **Batch Processing** - Use async endpoints for large datasets
- **Caching** - Store results to minimize redundant API calls

### Security
- **API Key Management** - Use environment variables, never hardcode keys
- **Data Privacy** - Follow GDPR/CCPA guidelines for personal data
- **Access Control** - Implement proper authentication in your applications

### Monitoring
- **Error Tracking** - Log API errors and response times
- **Usage Analytics** - Monitor API consumption and costs
- **Health Checks** - Implement service availability monitoring

## 🤝 Contributing

We welcome contributions to improve these tutorials:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/improvement`)
3. **Commit** your changes (`git commit -am 'Add new tutorial section'`)
4. **Push** to the branch (`git push origin feature/improvement`)
5. **Create** a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🆘 Support

- **Technical Issues** - [GitHub Issues](https://github.com/sixtyfour-ai/notebooks/issues)
- **API Support** - [support@sixtyfour.ai](mailto:support@sixtyfour.ai)
- **Sales Questions** - [sales@sixtyfour.ai](mailto:sales@sixtyfour.ai)

---

**Built with ❤️ by the SixtyFour team**
