# # AI Prompt Library 🤖

A curated collection of high-quality prompts for various AI models and use cases. This repository serves as a central hub for storing, organizing, and sharing effective prompts across different domains.

## 📁 Repository Structure

```
├── categories/
│   ├── coding/           # Programming and development prompts
│   ├── writing/          # Content creation and copywriting
│   ├── analysis/         # Data analysis and research prompts
│   ├── creative/         # Creative writing and brainstorming
│   ├── business/         # Business strategy and operations
│   └── personal/         # Personal productivity and learning
├── templates/            # Reusable prompt templates
├── workflows/            # Multi-step prompt sequences
├── examples/             # Sample outputs and use cases
└── tools/                # Scripts and utilities for prompt management
```

## 🏷️ Prompt Metadata

Each prompt file includes frontmatter with the following information:

```yaml
---
title: "Descriptive prompt title"
category: primary-category
subcategory: specific-area
tags: [tag1, tag2, tag3]
model_compatibility: [gpt-4, claude-3, gemini]
difficulty: beginner|intermediate|advanced
effectiveness: 1-5
created: YYYY-MM-DD
last_updated: YYYY-MM-DD
author: username
version: x.x
---
```

## 🚀 Quick Start

### Using a Prompt
1. Navigate to the appropriate category folder
2. Choose a prompt file that matches your needs
3. Copy the prompt content (excluding frontmatter)
4. Customize variables marked with `{placeholder}` syntax
5. Test with your preferred AI model

### Adding a New Prompt
1. Fork this repository
2. Create a new `.md` file in the appropriate category
3. Follow the naming convention: `purpose-specific-descriptor.md`
4. Include complete frontmatter metadata
5. Add usage examples and expected outputs
6. Submit a pull request

## 📋 Naming Conventions

- **Files**: Use kebab-case: `email-professional-response.md`
- **Categories**: Single word, lowercase: `coding`, `writing`
- **Tags**: Lowercase, descriptive: `python`, `marketing`, `analysis`

## ⭐ Effectiveness Rating System

- **5/5**: Exceptional results, works consistently across different contexts
- **4/5**: Very good results with minor tweaks needed
- **3/5**: Good baseline, requires customization for specific use cases
- **2/5**: Decent starting point, needs significant modification
- **1/5**: Basic prompt, requires substantial improvement

## 🔍 Finding Prompts

### By Category
Browse folders based on your primary use case:
- **Coding**: Software development, debugging, code review
- **Writing**: Blog posts, emails, documentation, creative content
- **Analysis**: Data interpretation, research, summarization
- **Creative**: Storytelling, brainstorming, ideation
- **Business**: Strategy, planning, communication
- **Personal**: Learning, productivity, decision-making

### By Tags
Search repository for specific tags:
- `python`, `javascript`, `sql` (programming languages)
- `email`, `blog`, `social-media` (content types)
- `beginner`, `advanced` (difficulty levels)
- `automation`, `analysis`, `creative` (use cases)

### Using GitHub Search
Use GitHub's search functionality:
- `filename:python` - Find all Python-related prompts
- `tag:email` - Search for email-related prompts
- `effectiveness:5` - Find highest-rated prompts

## 🛠️ Customization Guide

### Variables and Placeholders
Prompts use the following placeholder syntax:
- `{REQUIRED_INPUT}` - Must be replaced before use
- `[OPTIONAL_CONTEXT]` - Can be customized or removed
- `{{EXAMPLE}}` - Shows format, replace with actual content

### Model-Specific Adaptations
Some prompts include model-specific variations:
- **GPT-4**: Detailed instructions work well
- **Claude**: Prefers structured, step-by-step approaches
- **Gemini**: Benefits from explicit output format specifications

## 📊 Usage Examples

### Basic Usage
```markdown
**Prompt**: Write a professional email declining a meeting invitation

**Input Variables**: 
- {MEETING_TOPIC}: "Q3 Planning Session"
- {ORGANIZER_NAME}: "Sarah Johnson" 
- {REASON}: "conflicting priority project deadline"

**Expected Output**: Polite, professional email with alternative suggestions
```

### Advanced Workflow
For complex multi-step prompts, see the `workflows/` directory for chained prompt sequences.

## 📈 Performance Tracking

### Version History
- **v2.1** - Added business category, improved metadata structure
- **v2.0** - Major reorganization, added effectiveness ratings
- **v1.5** - Introduced workflow sequences
- **v1.0** - Initial repository structure


## 📞 Support and Feedback

- **Issues**: Suggest improvements
- **Discussions**: Share experiences and ask questions  
- **Email**: [itsrahulkumar7@gmil.com] for private inquiries

## 📄 License

This repository is licensed under the CC-NC. See [LICENSE](https://creativecommons.org/licenses/by-nc/4.0/deed.en) file for details.
