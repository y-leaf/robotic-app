Robotic application - named 'Wisteria'
====

## Requirement
pip install termcolor==1.1.0


## Usage

1. Executable by calling the talk_about_restaurant function as follows:

# vim main.py
import roboter.controller.conversation
roboter.controller.conversation.talk_about_restaurant()

2. Execute
$ python main.py


##option

If you want to change the CSV or template destination to be saved, put the following values in settings.py:

# vim settings.py
CSV_FILE_PATH = '/tmp/test.csv'
TEMPLATE_PATH = '/tmp/templates/'

# settings.pyファイルを作成した場合は、変更しない場合のDefaultは以下に設定する
CSV_FILE_PATH = None
TEMPLATE_PATH = None