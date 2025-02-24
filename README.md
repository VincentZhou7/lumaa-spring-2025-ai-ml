## Dataset

- **Source:** [TMBD Movie Dataset](https://www.kaggle.com/datasets/successikuku/tmbd-movie-dataset)
- **Description:** This data set contains information about 10,760 movies collected from The Movie Database (TMDb) between 1961 and 2015.

## Setup

### Prerequisites

- **Python Version:** Python 3.8+
- **Virtual Environment (Optional):**

```bash
python3 -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

## Running

To get movie recommendations based on a text query, open the jupyter notebook `recommendation.ipynb`, run all existing cells and run as the following example in a new cell:

```python
recommend_pipeline("I love thrilling action movies set in space, with a comedic twist.")
```

## Results

Example Output for Query: *"I love thrilling action movies set in space, with a comedic twist."*

```
Top 5 recommendations based on your query:
Showtime (Similarity 0.1580)
A spoof of buddy cop movies where two very different cops are forced to team up on a new reality based T.V. cop show.
---
Insidious: Chapter 3 (Similarity 0.1214)
A twisted new tale of terror begins for a teenage girl and her family, predating the haunting of the Lambert family in the earlier movies and revealing more mysteries of the otherworldly realm The Further.
---
Space Chimps (Similarity 0.1130)
Circus monkey Ham III works in a circus where he's regularly shot from a canon but he still lives in the shadow of his father's legacy. A natural born rebel against authority, Ham III is initially reluctant to go on a dangerous space mission to rescue a lost space probe, but away he goes, for lots of RIGHT STUFF-style astro-training alongside two highly prepared chimps, Luna and Titan.
---
Iron Sky (Similarity 0.1077)
In the last moments of World War II, a secret Nazi space program evaded destruction by fleeing to the Dark Side of the Moon. During 70 years of utter secrecy, the Nazis construct a gigantic space fortress with a massive armada of flying saucers.
---
You Only Live Twice (Similarity 0.1027)
A mysterious space craft kidnaps a Russian and American space capsule and brings the world on the verge of another World War. James Bond investigates the case in Japan and meets with his archenemy Blofeld. The fifth film from the legendary James Bond series starring Sean Connery as the British super agent.
---
```