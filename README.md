# 📘 awstronaut club Members Submission Guide

Welcome to awstronaut club! This project highlights K8SUG certified awstronaut community members around the world. You need to be fully certified on AWS first. Then, you need to claim your awstronaut title before you submit here. More info on [awstronaut](https://linkedin.com/company/awstronaut).

---

## 📥 How to Submit Your Profile

Please submit a JSON entry in `users.json` with the following structure, and upload your avatar image to the `avatars/` folder.

### ✅ JSON Format
```json
    {
    "name": "Yongkang He",
    "github": "yongkanghe",
    "certs": [
      "awstronaut",
      "kubestronaut"
    ],
    "provider": "K8SUG",
    "city": "Melbourne",
    "country": "Australia",
    "date": "2024-07-01",
    "bio": "Founder @K8SUG | Creator @kubestrong & @awstronaut | kubestronaut | Akamai Advocate | AWS Builder | Azure MVP | Google GDE | Alibaba MVP | Multi-Cloud | Community Reach | DevRel | 100K Social Reach",
    "twitter": "yongkanghe",
    "linkedin": "yongkanghe",
    "website": "https://k8sug.ai",
    "avatar": "/avatars/yongkanghe.png"
  }
```

### 📌 Field Descriptions
| Field      | Required | Description |
|------------|----------|-------------|
| `name`     | ✅       | Full name or display name |
| `github`   | ✅       | GitHub username (used for fallback avatar) |
| `certs`    | ✅       | Array of certification codes (e.g., `CKA`, `CKAD`) |
| `provider` | ✅       | Certification provider (usually `CNCF`) |
| `city`     | ✅       | City of residence |
| `country`  | ✅       | Country name (should match country name on the map) |
| `date`     | ✅       | Date of certification (format: `YYYY-MM-DD`) |
| `bio`      | ❌       | Short description or personal motto |
| `twitter`  | ❌       | Twitter handle (omit @) |
| `linkedin` | ❌       | LinkedIn username (not full URL) |
| `website`  | ❌       | Personal or portfolio website |
| `avatar`   | ❌       | Custom avatar image path (within `/avatars/`) |

---

## 🖼️ Avatar Upload Guidelines
- Upload your avatar image to the `avatars/` folder (e.g., `avatars/yourgithubusername.png`)
- **Max image size: 500 KB**
- **Recommended dimensions: 200x200 px** (square images display best)
- File format: `.png` or `.jpg`

> If no custom avatar is provided, we will use your GitHub profile picture.

---

## 💡 PR Tips
- Place your JSON entry in `users.json` to the end of the file
- Ensure valid JSON syntax (use a linter or JSON validator)
- Use meaningful commit messages (e.g., `add: alicejohnson to certified list`)

---

## 🙌 Thanks for contributing to the global awstronaut community!

