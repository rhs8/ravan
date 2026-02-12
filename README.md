# Ravan

**Ravan** (روان) Farsi for "flowing" and "mind"

A platform that uses technology to help people understand, learn, and preserve the intelligence of physical movement that has been treated as separate from intelligence. We value the mind and tend to overlook the body, even though a dancer's precision, an athlete's instinct, and a martial artist's discipline are all forms of knowledge. Movement *is* intelligence. The body learns, remembers, and expresses in ways words struggle to capture.

## Ravan exists to bridge that gap

It is centered on three ideas:

1. Use technology to see and interpret what the body is doing.
2. Help people learn movements by comparing their own to references and getting clear feedback. Do a move and learn its name or the history behind it.
3. Document movement traditions that are hard to put into words and easy to lose across generations.

Dance, sports, martial arts, physical therapy, wherever movement carries meaning, Ravan aims to support it.

---

## The Plan

We start with **dance movements**, a rich, expressive domain where the value is immediate. But the same technology translates to *all* categories of physical movement, from the slightest gestures to the largest motions.

**Health & safety** : Symptom detection, rehabilitation, workplace ergonomics, drowsy/distracted driving  
**Accessibility** : Sign language, fall detection, gesture-based interfaces  
**Learning & mastery** : Surgery, lab skills, crafts, handwriting, sports technique, productivity  
**Performance & creative** : Photography poses, theatre, music, animation, fashion  
**Development & care** : Child milestones, elderly gait and balance

The underlying capability, seeing, comparing, and interpreting how bodies move, applies everywhere. Dance is the beginning, not the limit.

---

## Tech Stack

| Component | Technology |
|-----------|------------|
| Pose Estimation | MediaPipe |
| Backend | Python, FastAPI |
| Comparison Logic | Dynamic Time Warping |
| Frontend | React |

---

## Project Structure

```
Ravan/
├── backend/
│   ├── app/
│   │   ├── main.py              # API endpoints
│   │   ├── pose_extractor.py    # Extract pose from video
│   │   ├── pose_comparator.py   # Compare movements
│   │   └── utils.py             # Helpers
│   ├── data/references/         # Reference movement library
│   └── requirements.txt
└── frontend/
    └── src/
```

---

## Status

🚧 **Early Development** Building the foundation.


---

*"The body knows things the mind has forgotten."*