<div align="center">

# Performance Evaluation of LLMs

</div>

| **Model**     | **Difficulty** | **Return Rate (%)** | **Similarity** | **Robustness** | **Confidence** | **Misalignment** |
|:-------------:|:--------------:|:-------------------:|:--------------:|:--------------:|:--------------:|:----------------:|
|               | Easy           | 6.50                | 41.06          | 43.40          | 92.50          | 14.50            |
| GPT-4o        | Medium         | 2.00                | 36.19          | 36.20          | 91.76          | 13.00            |
|               | Hard           | 0.05                | 24.13          | 19.70          | 89.47          | 16.00            |
|               | Easy           | 9.00                | 48.13          | 51.20          | 96.26          | 08.00            |
| GPT-o1        | Medium         | 3.00                | 43.87          | 44.90          | 92.57          | 08.00            |
|               | Hard           | 0.05                | **29.91**      | **38.50**      | 94.25          | 07.00            |
|               | Easy           | **11.50**           | **61.71**      | **54.40**      | 88.17          | **05.00**        |
| Gemini1.5-Pro | Medium         | **5.00**            | **47.34**      | **45.90**      | 93.97          | **07.50**        |
|               | Hard           | **0.20**            | 29.56          | 37.50          | 87.46          | **06.00**        |
|               | Easy           | 4.50                | 42.78          | 38.58          | 86.52          | 12.50            |
| Llama3.3-70B  | Medium         | 1.50                | 39.29          | 27.40          | 85.63          | 11.00            |
|               | Hard           | 0.15                | 24.87          | 13.60          | 92.15          | 16.00            |
|               | Easy           | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |
| Deepseek      | Medium         | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |
|               | Hard           | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |
|               | Easy           | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |
| Claude        | Medium         | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |
|               | Hard           | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |
|               | Easy           | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |
| Grok          | Medium         | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |
|               | Hard           | X.XX                | XX.XX          | XX.XX          | XX.XX          | XX.XX            |

*Each metric was evaluated using 2,000 valid samples, with each sample tested six times. Note that all metrics, except for "misalignment," are calculated exclusively using routes that can be parsed by Path Builder. Routes that cannot be generated are excluded from the benchmark and are not included in the 2,000 samples.*



# City Route Characteristics by Difficulty Level

| City | Difficulty | Avg. Length | Avg. Turns | Complexity |
|:----:|:----------:|:-----------:|:----------:|:----------:|
| -    | Easy       | 917         | 4.1        | 0.22       |
| Toronto | Medium  | 1612        | 7.5        | 0.48       |
| -    | Hard       | 2142        | 12.7       | 0.72       |
| -    | Easy       | 923         | 4.0        | 0.21       |
| Denver | Medium   | 1623        | 7.2        | 0.46       |
| -    | Hard       | 2122        | 12.3       | 0.70       |
| -    | Easy       | 912         | 4.5        | 0.24       |
| Mexico City | Medium | 1598     | 7.7        | 0.50       |
| -    | Hard       | 2117        | 12.9       | 0.74       |
| -    | Easy       | 935         | 4.6        | 0.25       |
| São Paulo | Medium | 1642       | 7.8        | 0.49       |
| -    | Hard       | 2154        | 13.2       | 0.73       |
| -    | Easy       | 903         | 4.3        | 0.23       |
| London | Medium   | 1604        | 7.4        | 0.47       |
| -    | Hard       | 2105        | 12.5       | 0.71       |
| -    | Easy       | 946         | 4.5        | 0.22       |
| Munich | Medium   | 1681        | 7.7        | 0.49       |
| -    | Hard       | 2202        | 13.1       | 0.71       |
| -    | Easy       | 877         | 5.1        | 0.27       |
| Tokyo | Medium    | 1596        | 8.1        | 0.52       |
| -    | Hard       | 2076        | 13.5       | 0.76       |
| -    | Easy       | 895         | 4.8        | 0.26       |
| Singapore | Medium | 1612       | 7.9        | 0.51       |
| -    | Hard       | 2095        | 13.3       | 0.75       |
| -    | Easy       | 947         | 4.2        | 0.22       |
| Sydney | Medium   | 1635        | 7.3        | 0.47       |
| -    | Hard       | 2136        | 12.6       | 0.72       |
| -    | Easy       | 919         | 4.3        | 0.23       |
| Auckland | Medium | 1627        | 7.5        | 0.48       |
| -    | Hard       | 2129        | 12.6       | 0.71       |
| -    | Easy       | 908         | 4.7        | 0.25       |
| Cairo | Medium    | 1607        | 7.8        | 0.50       |
| -    | Hard       | 2110        | 13.0       | 0.73       |
| -    | Easy       | 915         | 4.6        | 0.24       |
| Cape Town | Medium | 1618       | 7.6        | 0.49       |
| -    | Hard       | 2125        | 12.8       | 0.72       |


# City-based Return Rate Performance (%)

| **City** | **Difficulty** | **GPT-4o** | **GPT-o1** | **Gemini1.5-Pro** | **Llama3.3-70B** | **Deepseek** | **Claude** | **Grok** |
|:--------:|:-------------:|:----------:|:----------:|:-----------------:|:----------------:|:------------:|:----------:|:--------------:|
|  -       | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Toronto  | Medium       |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Denver   | Medium       |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Mexico City | Medium    |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| São Paulo | Medium      |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| London   | Medium       |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Munich   | Medium       |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Tokyo    | Medium       |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Singapore | Medium      |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Sydney   | Medium       |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Auckland | Medium       |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Cairo    | Medium       |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Easy         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| Cape Town | Medium      |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |
| -        | Hard         |    XX.XX   |    XX.XX   |       XX.XX       |      XX.XX       |    XX.XX     |   XX.XX    |     XX.XX      |


# Temperature performance for GPT4o under route reversal

| Temperature | Return Rate (%) | Similarity | Robustness | Confidence | Misalignment |
|-------------|-----------------|------------|------------|------------|--------------|
| 0.0         |      6.70       |    41.12   |    43.50   |    92.60   |     14.20    |
| 0.1         |      6.50       |    41.01   |    42.90   |    92.30   |     14.70    |
| 0.2         |      6.40       |    40.76   |    42.59   |    93.10   |     15.10    |
| 0.3         |      6.20       |    40.30   |    42.31   |    92.77   |     15.40    |
| 0.4         |      6.10       |    40.12   |    41.70   |    93.21   |     16.20    |
| 0.5         |      6.10       |    40.00   |    40.96   |    92.78   |     16.70    |
| 0.6         |      6.10       |    39.96   |    40.42   |    91.87   |     17.10    |
| 0.7         |      5.90       |    39.44   |    40.05   |    93.15   |     17.40    |
| 0.8         |      5.80       |    38.78   |    39.87   |    92.67   |     17.60    |
| 1.0         |      5.50       |   38.54    |    39.23   |    92.31   |     17.90    |
