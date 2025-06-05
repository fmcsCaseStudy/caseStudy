# UppaalTD: a Formal Tower Defense Game

<p align="center">
  <img src="https://cdn.worldvectorlogo.com/logos/politecnico-di-milano.svg" alt="Politecnico di Milano" width="250">
</p>

Tower defense games are a genre of strategy games in which players must defend a designated asset, which is commonly referred to as the Main Tower, against waves of incoming enemies. The player achieves this by strategically placing various types of turrets on a map to intercept and eliminate enemies before they reach the objective.

This repository contains the code used to present a formal analysis of a Tower Defense Game using Uppaal, a model checker for real-time systems based on networks of timed automata. The goal is to create a formal model of the game mechanics and verify key behavioral properties of the system under both deterministic (vanilla) and stochastic conditions. The analysis is conducted aiming to verify that the game behaves correctly and consistently under various configurations.

Through formal modeling and verification, enemy movement, turret behavior, and different game outcomes are examined to ensure that the system satisfies the intended rules and constraints. The final objective is to assess whether specific turret configurations lead to a win or loss and to quantify system behavior under uncertainty using Uppaal.


## 🚀 Getting Started

### System Configuration used for verifying queries
- Laptop: Lenovo ThinkBook
- Processor: AMD Ryzen AI 9 365
- RAM: 32 GB (minimum 8 GB allocated required, if not heap error)
- OS: Windows 11 24H2
- UPPAAL Version: 5.0.0

### Project Structure:
```bash
caseStudy/
├── Documents/                                      # Contains problem statement and the report pdf
├── Research & Ideas/                               # initial research and ideas used for modelling
├── Stochastic_Version                              
│   ├── TowerDefenseStochasticVersion.xml           # Stochastic Version XML File
├── Vanilla_Version                                 
│   ├── Backup Files/                               # older models which were optimized later
│   ├── TowerDefenseVanillaVersion.xml              # Vanilla Version XML File
```

## 🎭 Contributors

<table>
    <tr>
        <th>Name</th>
        <th>Course</th>
    </tr>
    <tr>
            <td><strong>Ali Bassam</strong></td>
            <td>MSc Computer Science & Engineering</td>
    </tr>
    <tr>
            <td><strong>Leonardo Carlo Conti </strong></td>
            <td>MSc Computer Science & Engineering</td>
    </tr>
    <tr>
            <td><strong>Satvik Sharma</strong></td>
            <td>MSc Computer Science & Engineering</td>
    </tr>
    <tr>
            <td><strong>Shi Zhi Qiang </strong></td>
            <td>MSc Computer Science & Engineering</td>
    </tr>
</table>
