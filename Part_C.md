Q1 — What is the difference between PMF and PDF?
Q2 (Coding) — Write a function to compute probability of an event from frequency data (relative frequency approach).
Q3 — What is the Central Limit Theorem? Why is it important in machine learning?

ans1:
PMF: discrete probability
PDF: continuous probability density

ans2:
def probability(event, data):
    return data.count(event) / len(data)

ans3:
Mean of samples → normal distribution
Important for:
statistical inference
ML assumptions