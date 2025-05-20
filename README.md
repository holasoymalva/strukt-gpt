# 🏗️ Strukt GPT 🦙

> *"Infrastructure as simple as ordering tacos."*

![Strukt Banner](https://placehold.co/1200x300/5046e4/ffffff?text=Strukt+GPT:+Infrastructure+through+conversation&font=montserrat)

[![Version](https://img.shields.io/badge/version-0.1.0-brightgreen)](https://github.com/holasoymalva/strukt-gpt)
[![Status](https://img.shields.io/badge/status-MVP-orange)](https://github.com/holasoymalva/strukt-gpt)
[![Made with 💜 in LATAM](https://img.shields.io/badge/made%20with%20%F0%9F%92%9C-in%20LATAM-blueviolet)](https://github.com/holasoymalva)

## 🪄 What is Strukt?

Strukt is like that engineer friend who always solves everything - but for your cloud infrastructure. It's an AI application that converts your everyday language descriptions into professional Terraform code, without having to learn HCL or remember AWS syntax.

**Example:**
> "I need a Lambda that triggers when files are uploaded to S3 and stores data in DynamoDB"

And BOOM! 💥 You have Terraform code ready to deploy. That simple.

## 🚀 Features

- 🗣️ **Conversational Infrastructure**: Describe it like you'd explain it to your grandma
- 🧠 **Powered by Claude**: The AI that truly understands what you need
- ☁️ **AWS Focused**: For now just AWS, but soon GCP and Azure (patience, amigo!)
- 📋 **Production-Ready Code**: No more copying and pasting from StackOverflow
- 🔄 **Continuous Conversation**: Refine your infrastructure with follow-up questions

## 🖥️ Demo

![Strukt Demo](https://placehold.co/800x450/48507c/ffffff?text=Strukt+GPT+Demo&font=montserrat)

## 🛠️ Installation

Eager to try it? Here's everything you need:

### Prerequisites
- Node.js (v16+)
- NPM or Yarn
- An Anthropic API key (for Claude)
- Coffee and snacks for your coding session (optional but recommended)

### Local Installation

```bash
# Clone the repo, with enthusiasm!
git clone https://github.com/holasoymalva/strukt-gpt.git

# Enter the directory like you own the place
cd strukt-gpt

# Install dependencies (grab a coffee while you wait)
npm install
# or if you're team Yarn
yarn install

# Create a .env.local file and add your API key
echo "ANTHROPIC_API_KEY=your_secret_key_here" > .env.local

# Let's roll!
npm run dev
# or with Yarn
yarn dev
```

Now open your browser at `http://localhost:3000` and voilà! Start generating infrastructure like it's a party.

## 🌎 Deployment on Vercel

Want to show off to your friends? Deploy it on Vercel!

1. Fork this repo (or clone it to your account)
2. Connect it to [Vercel](https://vercel.com)
3. Set up your `ANTHROPIC_API_KEY` environment variable
4. Hit "Deploy" and BOOM! 💥 Your app in production

## 👨‍💻 Usage

### 1. Describe your infrastructure

```
I want a Kubernetes cluster with autoscaling and monitoring for our food delivery application
```

### 2. Magically get Terraform code

```hcl
# Provider configuration
provider "aws" {
  region = var.region
}

# Variables
variable "region" {
  description = "AWS region"
  default     = "us-east-1"
}

variable "cluster_name" {
  description = "Name of the EKS cluster"
  default     = "food-delivery-cluster"
}

# ... more magnificent Terraform code ...
```

### 3. Deploy and enjoy!

## 🤝 Contributions

We want your help to make Strukt something awesome!

1. Fork the repo (don't be shy)
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Added support for amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request and you're done!

## 🗺️ Roadmap

- [ ] GCP support (coming soon!)
- [ ] Azure support (also coming soon, but a bit later)
- [ ] User authentication (to save your favorite infras)
- [ ] Terraform Cloud integration
- [ ] Mobile app (for infrastructure on the go)
- [ ] "Weekend Mode" - infrastructure optimization for the weekend

## 🧠 The Team Behind Strukt

We're a team of LATAM engineers obsessed with making infrastructure as easy as ordering food delivery.

## 🔐 Security

We don't store your code. What happens in Strukt, stays in Strukt (unless you save it).

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- To all the grandmothers who inspired this project with their questions like "What's this cloud thing, sonny?"
- To the coffee providers who kept our team running
- To all infrastructure engineers who have suffered writing Terraform by hand

---

<p align="center">
  <img src="https://placehold.co/150x150/5046e4/ffffff?text=Strukt&font=montserrat" alt="Strukt Logo">
</p>

<p align="center">
  Made with 💜 from LATAM to the world
</p>

<p align="center">
  <a href="https://twitter.com/holasoymalva">Twitter</a> •
  <a href="https://github.com/holasoymalva">GitHub</a> •
  <a href="https://www.linkedin.com/in/malvabombom/">LinkedIn</a>
</p>
