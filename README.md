# knowledge-driven-dialogue
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# about the competition
Human-machine conversation is one of the most important topics in artificial intelligence (AI) and has received much attention across academia and industry in recent years. Currently dialogue system is still in its infancy, which usually converses passively and utters their words more as a matter of response rather than on their own initiatives, which is different from human-human conversation. Therefore, we set up this competition on a new conversation task, named knowledge driven dialogue, where machines converse with humans based on a built knowledge graph. It aims at testing machines’ ability to conduct human-like conversations.
Please refer to [competition website](http://lic2019.ccf.org.cn/talk) for details of the competition.
# about the task
Given a dialogue goal g and a set of topic-related background knowledge M = f1 ,f2 ,..., fn , a participating system is expected to output an utterance "ut" for the current conversation H = u1, u2, ..., ut-1, which keeps the conversation coherent and informative under the guidance of the given goal. During the dialogue, a participating system is required to proactively lead the conversation from one topic to another. The dialog goal g is given like this: "Start->Topic_A->TOPIC_B", which means the machine should lead the conversation from any start state to topic A and then to topic B. The given background knowledge includes knowledge related to topic A and topic B, and the relations between these two topics.
Please refer to [task description](https://github.com/baidu/knowledge-driven-dialogue/blob/master/task_description.pdf) for details of the task.
