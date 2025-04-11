# ReMADE-14: A Reconstruction-based Multi-stage Attack Dataset for Evaluating IDS Models

**ReMADE-14** is a reconstruction-based MSA (Multi-Stage Attack) dataset that includes 14 realistic and diverse MSA scenarios. The dataset is constructed by systematically integrating real-world attack vectors extracted from the AWID3 dataset. This dataset is designed to serve as a robust benchmark for evaluating IDS (Intrusion Detection System) models under temporally structured and sophisticated attack conditions.

## Dataset Structure

- Each MSA scenario is saved as a folder
- Each folder contains **multiple `.csv` files**, each holding **50,000 records**
- Each row includes preprocessed features and a corresponding label (e.g., normal or specific attack stage)
- Stage-wise metadata is provided separately for reference

| Scenario | Attack Stages                                  |
|----------|-------------------------------------------------|
| 1        | Deauthentication + Evil Twin + Website Spoofing |
| 2        | Evil Twin + (Re)Association + Website Spoofing  |
| 3        | Malware + Botnet                                |
| 4        | SQL Injection + Malware                         |
| 5        | Rogue AP + Krack + Kr00k                        |
| 6        | SSH + Botnet                                    |
| 7        | (Re)Association + Malware                       |
| 8        | Evil Twin + Malware                             |
| 9        | Krack + Botnet                                  |
| 10       | SSH + SQL Injection                             |
| 11       | Kr00k + SSH                                     |
| 12       | Website Spoofing + SQL Injection                |
| 13       | Deauthentication + Kr00k                        |
| 14       | SSDP + Rogue AP                                 |

## Dataset Download

You can download the full dataset from the following link:

🔗 [Download ReMADE-14 Dataset](https://naver.me/FO9k3gcO)

## Contact

E-mail : sw.hong@yonsei.ac.kr
