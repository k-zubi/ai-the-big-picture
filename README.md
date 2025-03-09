# AI: The Big Picture

A comprehensive overview of the past, present, and future of frontier AI development. This project consists of a LaTeX presentation that explores various aspects of the AI landscape, from technical scaling to geopolitical implications.

**[View the full presentation (PDF)](presentation/presentation.pdf)**

## Project Structure

- `presentation/presentation.tex`: Main LaTeX source file for the presentation
- `presentation/references.bib`: Bibliography file with all references
- `presentation/images/`: Directory containing all images used in the presentation
- `presentation/presentation.pdf`: Compiled PDF version of the presentation

## Overview

Summaries of all the sections:

### Scaling

- The training compute of frontier AI models continues to grow by 4-5x per year, following a log-linear scaling trend that has persisted for over a decade.
- Improving AI performance requires more compute through scaling model size, data quantity, data quality, or architecture efficiency.
- Scaling laws reliably predict model loss, but benchmark performance is significantly less predictable.
- Epoch AI's analysis identifies electric power, chip manufacturing, data availability, and latency as key constraints that must be overcome to maintain the current scaling trajectory through 2030.

### Data and Architecture

- Language model training involves three distinct phases: pre-training, instruction-tuning, and now reinforcement learning (RL) to scale reasoning.
- The industry faces a "data wall" within five years at current scaling trends.
- AI-generated training data is increasingly used but brings risks, making verification of generated content crucial for maintaining quality.
- Reasoning models represent a fundamental shift, enabling breakthrough performance in areas where previous models significantly underperformed humans.
- These models require more inference compute but may help overcome the looming "data wall" since RL training appears more data-efficient than pre-training.
- Despite impressive gains in reasoning, planning, math and coding, reasoning models have barely been scaled so far due to them only being discovered recently.
- The potential application of RL to agent training could transform AI autonomy, though significant challenges and uncertainties remain.

### Finance

- Amazon, Google, Microsoft and Meta are each making their most expensive bet yet with each of them roughly doubling their total capital expenditures in the past two years in order to spend unprecedented amounts on AI infrastructure.
- The annualized spending on AI infrastructure of each of these companies is now reaching the annual costs of the most expensive megaprojects ever (such as the Apollo program).

### Chips

- Hardware used for AI training has evolved from graphics cards to specialized AI accelerators, with future directions including ASICs, in-memory computing, and experimental technologies like photonic and neuromorphic computing.
- NVIDIA dominates the AI hardware market, experiencing a 10x increase in data center revenue over two years while maintaining huge profit margins.
- Major tech companies including Google, Amazon, Meta and Microsoft have developed their own AI accelerators to reduce reliance on NVIDIA and lower costs, with Google's TPU series showing particular maturity.
- The computing capacity for AI is highly concentrated, with these four companies estimated to have purchased about half of all NVIDIA data center GPUs.
- While manufacturing constraints exist, particularly in chip packaging and high-bandwidth memory, current projections (with high uncertainty) suggest the chip industry can produce enough GPUs for AI training through 2030.

### Power

- Frontier AI models in 2030 could require interconnected data centers with a capacity of approximately 6 gigawatts for a single training run, posing unprecedented power infrastructure challenges.
- The U.S. Department of Energy and the PJM Interconnection project a significant, yet likely manageable, increase in total electricity demand, a major shift from previously flat electricity demand forecasts.
- Major tech companies are pursuing gigawatt-scale data centers connected to existing power plants, building new power plants, and exploring nuclear energy options through agreements with energy companies.
- The largest planned data centers will each rank among the most expensive factories ever built and among the most expensive megaprojects in U.S. history.

### Geopolitics

- The U.S. leads the world in AI investment, while both the U.S. and China lead in AI research.
- The U.S. has implemented increasingly stringent chip export restrictions to China (and now almost all countries of the world), limiting access to AI accelerators.
- Both the Biden and Trump administrations have elevated AI to a matter of national security and economic competitiveness, with both taking measures to streamline construction of gigawatt-scale data centers and Trump declaring the first ever national energy emergency partly to power AI.
- Europe, led by France, is mounting a significant response with multi-billion euro investments to build data centers, though still lagging behind the U.S.

## License

This project is licensed under the MIT License.