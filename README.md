# 🎨 Public Assets CDN

**Free-to-use icons, logos, and brand assets for developers and creators.**

Served via GitHub Pages CDN — fast, reliable, globally distributed.

---

## 📦 Usage

Reference any asset directly in your HTML, CSS, or Markdown:

```html
<img src="https://samuelsjames.github.io/assets-public/logos/tools/aws-logo.svg" alt="AWS">
```

```css
background-image: url('https://samuelsjames.github.io/assets-public/brand/gh-bg.png');
```

```markdown
![Cisco](https://samuelsjames.github.io/assets-public/logos/tools/cisco-blue-logo.svg)
```

No downloads required. No attribution required. Just link and use.

---

## 📂 Structure

```
assets-public/
├── logos/
│   ├── aws/          AWS service icons (EC2, S3, VPC, Lambda, etc.)
│   ├── tools/        Dev & infra tools (Cisco, Ansible, Bash, Python, Linux, Git)
│   └── platforms/    Platform logos (GitHub, Gitea)
├── icons/            UI icons and illustrations
├── brand/            Backgrounds, textures, profile assets
└── README.md
```

---

## 🗂️ Available Assets

### AWS Service Icons (`logos/aws/`)
| Asset | Preview | URL |
|-------|---------|-----|
| EC2 | ☁️ | `logos/aws/ec2-icon.svg` |
| S3 | ☁️ | `logos/aws/s3-icon.svg` |
| CloudWatch | ☁️ | `logos/aws/cloudwatch-icon.svg` |
| CloudFormation | ☁️ | `logos/aws/cloudformation-icon.svg` |
| VPC | ☁️ | `logos/aws/vpc-icon.svg` |
| Lambda | ☁️ | `logos/aws/lambda-icon.svg` |
| Route 53 | ☁️ | `logos/aws/route53-icon.svg` |
| IAM Identity Center | ☁️ | `logos/aws/iam-identity-center-icon.svg` |
| KMS | ☁️ | `logos/aws/kms-icon.svg` |
| Budgets | ☁️ | `logos/aws/budgets-icon.svg` |

### Dev & Infra Tools (`logos/tools/`)
| Asset | URL |
|-------|-----|
| AWS Logo | `logos/tools/aws-logo.svg` |
| Cisco (Blue) | `logos/tools/cisco-blue-logo.svg` |
| Ansible | `logos/tools/ansible-color-logo.svg` |
| Linux (Tux) | `logos/tools/linux-logo.svg` |
| Bash | `logos/tools/bash-logo.svg` |
| Python | `logos/tools/python-logo.svg` |
| Cloud Networking | `logos/tools/cloud-networking-logo.svg` |

### Platforms (`logos/platforms/`)
| Asset | URL |
|-------|-----|
| GitHub | `logos/platforms/github-logo.svg` |
| Gitea | `logos/platforms/gitea-logo.svg` |

### Brand Assets (`brand/`)
| Asset | Description | URL |
|-------|-------------|-----|
| gh-bg.png | Dark navy circuit board background | `brand/gh-bg.png` |
| profile.jpg | Professional headshot | `brand/profile.jpg` |

---

## 🌐 Base URL

All assets are available at:

```
https://samuelsjames.github.io/assets-public/
```

Append the file path from the structure above to get the full URL.

---

## 📋 License

**Free to use.** These assets are provided for anyone to use in personal or commercial projects. No attribution required, though a star ⭐ on this repo is always appreciated.

Some assets (AWS icons, Cisco logos, etc.) are trademarks of their respective companies and are included here for convenience in technical documentation and portfolio projects. Use them in accordance with each company's brand guidelines.

---

## 🤝 Contributing

Have a useful SVG or icon that should be here? Open a PR. Keep files:
- SVG preferred (vector, small file size)
- PNG only when SVG isn't available
- Optimized (no unnecessary metadata)
- Organized in the correct folder

---

## ⚡ Why This Exists

Instead of duplicating the same logos and icons across every project repo, this single CDN serves them all. One update here propagates everywhere instantly. Less repo bloat, faster builds, cleaner code.

---

Made with 🛠️ by [Samuel James](https://samuelsjames.github.io/samjam-tech/)
