# 🎨 Public Assets CDN

**Free-to-use icons, logos, and brand assets served via GitHub Pages.**

---

## 📐 Naming Convention

| Type | Suffix | Example | Description |
|------|--------|---------|-------------|
| **Logo** | `*-logo` | `aws-logo.svg` | Brand or company identity mark. Represents the whole entity. |
| **Icon** | `*-icon` | `ec2-icon.svg` | Service or product icon. Represents a specific feature/service within a brand. |
| **Background** | `*-bg` | `gh-bg.png` | Reusable background texture or pattern. |

**Variant naming:** Use descriptive prefixes for color/style variants:
- `cisco-blue-logo.svg` — blue variant
- `ansible-color-logo.svg` — full color variant
- `samjam-orange-logo.svg` — orange brand variant (planned)
- `samjam-green-logo.svg` — green brand variant (planned)

---

## 📂 Structure

```
assets-public/
├── logos/           Brand & company logos (*-logo)
├── icons/
│   ├── aws/         AWS service icons (*-icon)
│   └── wellness/    SA Wellness Platform icons (*-icon)
├── backgrounds/     Reusable backgrounds (*-bg)
├── brand/           Personal brand (profile photo, headshots, dashboard brands)
├── graphics/        Illustrations, dividers, decorative UI elements
└── README.md
```

### Key differences:
- **logos/** = The company/tool *itself* (AWS, Cisco, Linux, Python)
- **icons/** = A *product or service within* a company or app (EC2, Lambda, dashboard-icon)
- **backgrounds/** = Textures/patterns usable across any project
- **brand/** = Personal/project identity assets (headshots, dashboard brands)
- **graphics/** = Decorative illustrations, dividers, activity art (not icons or logos)

### Metadata
Each folder contains a `metadata.md` file describing every asset: filename, description, source, and project context.

---

## 🌐 Base URL

```
https://samuelsjames.github.io/assets-public/
```

---

## 📦 Usage

```html
<img src="https://samuelsjames.github.io/assets-public/logos/aws-logo.svg" alt="AWS">
<img src="https://samuelsjames.github.io/assets-public/icons/aws/ec2-icon.svg" alt="EC2">
```

```css
background-image: url('https://samuelsjames.github.io/assets-public/backgrounds/gh-bg.png');
```

---

## 🗂️ Asset Catalog

### Logos (`logos/`)

| Preview | File | Brand | Colors | Notes |
|---------|------|-------|--------|-------|
| <img src="logos/aws-logo.svg" width="24"> | `aws-logo.svg` | Amazon Web Services | `#232F3E` (dark), `#FF9900` (orange) | Full AWS wordmark |
| <img src="logos/cisco-blue-logo.svg" width="24"> | `cisco-blue-logo.svg` | Cisco | `#049FD9` (blue) | Blue bridge mark |
| <img src="logos/ansible-color-logo.svg" width="24"> | `ansible-color-logo.svg` | Ansible (Red Hat) | `#1A1918` (black), `#EE0000` (red) | Full color "A" mark |
| <img src="logos/linux-logo.svg" width="24"> | `linux-logo.svg` | Linux (Tux) | `#000000`, `#FCC624` (yellow) | Tux penguin mascot |
| <img src="logos/bash-logo.svg" width="24"> | `bash-logo.svg` | GNU Bash | `#4EAA25` (green), `#293036` (dark) | Shell logo |
| <img src="logos/python-logo.svg" width="24"> | `python-logo.svg` | Python | `#3776AB` (blue), `#FFD43B` (yellow) | Dual-snake mark |
| <img src="logos/cloud-networking-logo.svg" width="24"> | `cloud-networking-logo.svg` | Generic | `#0A7CD1` (blue) | Cloud + network icon |
| <img src="logos/github-logo.svg" width="24"> | `github-logo.svg` | GitHub | `#181717` (black) | Octocat mark |
| <img src="logos/gitea-logo.svg" width="24"> | `gitea-logo.svg` | Gitea | `#609926` (green) | Tea cup mark |

### Icons (`icons/aws/`)

| Preview | File | Service | Colors | Notes |
|---------|------|---------|--------|-------|
| <img src="icons/aws/ec2-icon.svg" width="24"> | `ec2-icon.svg` | Elastic Compute Cloud | `#ED7100` (orange) | Compute service |
| <img src="icons/aws/s3-icon.svg" width="24"> | `s3-icon.svg` | Simple Storage Service | `#569A31` (green) | Object storage |
| <img src="icons/aws/cloudwatch-icon.svg" width="24"> | `cloudwatch-icon.svg` | CloudWatch | `#E7157B` (pink) | Monitoring & observability |
| <img src="icons/aws/cloudformation-icon.svg" width="24"> | `cloudformation-icon.svg` | CloudFormation | `#E7157B` (pink) | Infrastructure as code |
| <img src="icons/aws/vpc-icon.svg" width="24"> | `vpc-icon.svg` | Virtual Private Cloud | `#8C4FFF` (purple) | Network isolation |
| <img src="icons/aws/lambda-icon.svg" width="24"> | `lambda-icon.svg` | Lambda | `#ED7100` (orange) | Serverless compute |
| <img src="icons/aws/route53-icon.svg" width="24"> | `route53-icon.svg` | Route 53 | `#8C4FFF` (purple) | DNS service |
| <img src="icons/aws/iam-identity-center-icon.svg" width="24"> | `iam-identity-center-icon.svg` | IAM Identity Center | `#DD344C` (red) | Access management |
| <img src="icons/aws/kms-icon.svg" width="24"> | `kms-icon.svg` | Key Management Service | `#DD344C` (red) | Encryption keys |
| <img src="icons/aws/budgets-icon.svg" width="24"> | `budgets-icon.svg` | AWS Budgets | `#8C4FFF` (purple) | Cost management |

### Backgrounds (`backgrounds/`)

| File | Description | Colors | Use case |
|------|-------------|--------|----------|
| `gh-bg.png` | Dark navy circuit board / hexagon pattern | `#0D1117`, `#161B22` | Portfolio sites, dark themes |

### Brand (`brand/`)

| File | Description | Notes |
|------|-------------|-------|
| `profile.jpg` | Professional headshot | Personal use |

---

## 🎨 Color Reference (AWS Service Categories)

| Category | Hex | Services |
|----------|-----|----------|
| Compute | `#ED7100` | EC2, Lambda |
| Storage | `#569A31` | S3 |
| Networking | `#8C4FFF` | VPC, Route 53, Budgets |
| Security | `#DD344C` | IAM, KMS |
| Management | `#E7157B` | CloudWatch, CloudFormation |

---

## 📋 License

Free to use in personal or commercial projects. No attribution required.

Vendor logos (AWS, Cisco, etc.) are trademarks of their respective companies — use in accordance with their brand guidelines.

---

Made with 🛠️ by [Samuel James](https://samuelsjames.github.io/samjam-tech/)
