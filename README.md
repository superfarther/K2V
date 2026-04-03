<h1 style="text-align: center;">Knowledge-to-Verification: Unlocking Reinforcement Learning with Verifiable Rewards for LLMs in Knowledge-Intensive Domains</h1>

## What is K2V
K2V (Knowledge-to-Verification) is a framework that extends RLVR (Reinforcement learning ith verifiable Rewards) to knowledge-intensive domains and enabling verification of the model's reasoning process, without any human supervision.

## How to use
1. Clone the repository
    ```bash
    git clone --recurse-submodules https://github.com/superfarther/K2V.git
    cd K2V
    ```

2. Install the dependencies of **[graphgen-mask](https://github.com/superfarther/graphgen-mask.git)** according to the README, and then synthesize the fill-blank style QA pairs. 
    ```bash
    cd graphgen-mask
    vim README.md 
    ```

3. Synthsize question-specific checklist for each QA pair.
    ```bash
    cd utils
    vim README.md 
    ```

4. Install the dependencies of **[verl](https://github.com/superfarther/verl.git)** according to the README, and then start training. 
    ```bash
    cd verl
    vim README.md 
    ```




