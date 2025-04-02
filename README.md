# **The Results of Physical Distance on Wi-Fi Bandwidth**

**Author**: John McGinnes  
**Objective**: Investigating the impact of physical distance on Wi-Fi bandwidth (download/upload speeds) in a home network setting.

## **Overview**
This repository contains the results of an experiment that explores how distance from a wireless access point (WAP) affects Wi-Fi network performance. Using a basic home Wi-Fi setup, the study measures the attenuation of signal strength in the 2.4GHz and 5GHz bands over distances ranging from 0 feet to 100 feet. The goal is to determine how much network speed decreases as the distance from the WAP increases.

The experiment was conducted using a Lenovo Legion 7i laptop and a Nokia Wi-Fi Beacon 2. Speed tests were performed at incremental distances, and results were recorded for both download and upload speeds. The results showed a significant drop in network speeds as the distance increased, providing empirical data that supports theoretical research on signal attenuation.

## **Key Sections**
- **Introduction and Literature Review**: Discusses the theoretical background on electromagnetic waves and signal attenuation.
- **Hypothesis**: Predicts a decrease in Wi-Fi speeds of over 1mbps per foot as distance from the WAP increases.
- **Methodology**: Describes the experiment setup, including variables, equipment used, and the procedure for measuring signal strength.
- **Results**: Provides the data gathered from the experiment, showing how Wi-Fi bandwidth diminishes over varying distances.
- **Conclusions**: Confirms the hypothesis with results that show significant bandwidth reduction, and discusses potential confounding factors and limitations of the study.

## **Experiment Details**
- **Distance Range**: 0ft to 100ft from the Wi-Fi access point.
- **Speed Test Tool**: Cloudflare's online speed test (speed.cloudflare.com).
- **Wi-Fi Access Point**: Nokia Wi-Fi Beacon 2 on a Nokia x5-110g-a router.
- **ISP**: Fiber optic with a maximum speed of 250mbps.

## **Findings**
- **Significant Signal Loss**: Wi-Fi speeds decreased at an average rate of 2mbps per foot over the 100ft distance, with a total reduction of 227.3mbps download and 210.7mbps upload.
- **Impact of Obstacles**: Walls and obstructions in the testing environment affected signal attenuation and contributed to the overall loss in performance.

## **Sources**
- Sengupta, A. (2021). *Does Distance From the Wi-Fi Router Impact Download Speeds?* ScienceABC.
- CASDataloggers (2023). *The Basics of Signal Attenuation*.

For detailed results, testing procedure, and analysis, refer to the full research paper and associated data files in this repository.

