# question_generator

Question Generator is an NLP system for generating reading comprehension-style questions from texts such as news articles or pages excerpts from books. The system is built using pretrained models from [HuggingFace Transformers](https://github.com/huggingface/transformers). There are two models: the question generator itself, and the QA evaluator which ranks and filters the question-answer pairs based on their acceptability.

python run_qg.py --text_file articles/solarsystem.txt --answer_style all --num_questions 3
python run_qg.py --text_file articles/watercycle.txt --answer_style sentences --num_questions 5
python run_qg.py --text_file articles/humanbody.txt --answer_style all --num_questions 3
python run_qg.py --text_file articles/indian_matchmaking.txt --answer_style all --num_questions 5

