# SnapEats - Multimodal Nutrition Label Analyzer

**Google AI Hackathon Finalist | Top 25 of 898 submissions (15,498 total participants)**

**Live Demo:** [snapeats.flutterflow.app](https://snapeats.flutterflow.app) | **Devpost:** [devpost.com/software/snapeats](https://devpost.com/software/snapeats)

## What It Does

SnapEats lets users snap a photo of any nutrition label or ingredient list and get an instant, plain-language breakdown of what's in their food. The app categorizes ingredients as beneficial, concerning, or potentially harmful, and provides personalized dietary analysis based on user preferences.

The problem is simple: most people can't quickly interpret complex nutrition labels. SnapEats removes that friction with a camera tap.

## How It Works

```
Photo of nutrition label
    |
    v
[Gemini Vision API]
    - OCR extraction of label text
    - Ingredient identification and classification
    - Nutritional analysis against user dietary profile
    |
    v
[Personalized Summary]
    - Beneficial ingredients (green)
    - Concerning ingredients (yellow)
    - Potentially harmful ingredients (red)
    - Plain-language explanation
```

## Tech Stack

| Layer | Technology |
|-------|-----------|
| AI/ML | Google Gemini 1.5 Vision API |
| Prototyping | Google AI Studio, Google Colab |
| Frontend | FlutterFlow |
| Backend | Firebase, Google Cloud Platform |

## Results

- **Top 25** out of 898 project submissions
- **15,498** total hackathon participants
- **50+** users tested during development
- **~2 second** processing time per label scan
- **85%** of test users reported increased confidence in interpreting nutritional labels

## My Role

Led a 12-person cross-functional team as architect and Google Cloud integration lead. Conducted user research interviews, defined the product vision, coordinated rapid prototyping across three 48-hour iteration cycles, and led the Demo Day presentation.

## Context

Built in 48 hours for the **Google AI Hackathon** (May 2024) on Devpost. This was a precursor to my later production AI work on Sugoi and Arbiter at ConvoRecs.

## Author

**Yves Agbre** | [LinkedIn](https://www.linkedin.com/in/yagbre) | [GitHub](https://github.com/yagbre21)
