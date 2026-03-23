# SnapEats - AI Nutrition Label Analyzer

**Google AI Hackathon Finalist | Top 25 of 898 submissions (15,498 total participants)**

**Live Demo:** [snapeats.flutterflow.app](https://snapeats.flutterflow.app) | **Demo Video:** [YouTube](https://www.youtube.com/watch?v=vUXIyA2wPX8) | **Devpost:** [devpost.com/software/snapeats](https://devpost.com/software/snapeats)

## What It Does

SnapEats turns your phone camera into a nutrition translator. Point it at any food package, snap a photo of the nutrition label or ingredient list, and the app reads the label and breaks down ingredients and nutrition facts into plain language. No more deciphering chemical names or confusing percentages.

The app categorizes ingredients as beneficial, concerning, or potentially harmful, and provides personalized dietary analysis based on user preferences.

## How It Works

```
Phone camera pointed at food package
    |
    v
[Snap photo of nutrition label]
    |
    v
[Gemini Vision API]
    - Reads label directly from the image
    - Identifies and classifies every ingredient
    - Analyzes nutrition against user dietary profile
    |
    v
[Plain-Language Breakdown]
    - Beneficial ingredients (green)
    - Concerning ingredients (yellow)
    - Potentially harmful ingredients (red)
    - Personalized dietary recommendations
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
