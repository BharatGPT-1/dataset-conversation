
---

### **3. `dataset-conversations` (Chat Data)**
#### **README.md**
```markdown
# 💬 Conversation Datasets

**Purpose**: Curated dialogue data for chatbot fine-tuning.  
**Sources**:  
- Cornell Movie Dialogs  
- Persona-Chat  
- Custom scraped chats (CC-BY-SA).

## 📊 Stats
| Dataset        | Samples | Avg. Turns |
|---------------|---------|------------|
| Cornell Movie | 220k    | 3.2        |
| Persona-Chat  | 160k    | 4.5        |

## 🗂 Structure
cornell/ # train.jsonl, test.jsonl
persona/ # train_original.txt, train_revised.txt
preprocessed/ # Tokenized versions (for direct training)

text

## 🔄 Update Workflow
1. Run `scripts/format_cornell.py`.  
2. Validate with `scripts/stats.py`.

