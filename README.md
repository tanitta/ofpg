# ofpg
openFrameworksのprojectGeneratorの簡易的なワンライナーです．

## Usage
projectを作成したいディレクトリに移動した後，以下のコマンドでprojectを作成します．
	ofpg -n project_name -t template_name
ここで-nはprojectの名前を，-tは作成するprojectの元になるtemplateを指定します．なおtemplateはofpg/tmp内で定義できます．また，-tは省略可能です．その場合，defaultのtemplateを元にprojectが作成されます．
	
