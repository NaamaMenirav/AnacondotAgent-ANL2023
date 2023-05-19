# AnacondotAgent-ANL2023
A negotiation agent for bilateral negotiation that can learn from every previous encounter

# To whom it may concern

## i want to make sure that you will upload our agent accordingly, this is how it needs to be run in the "run.py" file


        {
            "class": "agents.colman_anacondot_agent2.colman_anacondot_agent2.ColmanAnacondotAgent2",
            "parameters": {"storage_dir": "agent_storage/ColmanAnacondotAgent2"},
        }

The Automated Negotiating Agent Competition (ANAC) [1] is an international 
tournament that has been running since 2010 to bring together researchers from 
the negotiation community. Our team took part in the Automated Negotiation 
League (ANL) 2023 [2], where the task is to design a negotiation agent for bilateral 
negotiation that can learn from every previous encounter while the tournament 
progresses. The highest-scoring agents based on individual utility and social welfare 
win.

The agent is designed to participate in multi-issue negotiations built in Python 
using the GeniusWeb environment, where each issue has discrete possible values. 
The critical components of the agent's design are the `OpponentModel` and 
`IssueEstimator` classes. These components enable the agent to estimate the 
opponent's preferences and use these estimates to generate bids that are likely to be 
acceptable to the opponent while maximizing their utility
