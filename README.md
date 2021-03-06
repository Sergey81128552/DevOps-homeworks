# DevOps-homeworks
1.1. Введение в DevOps — Сергей Емельянов
-----------------------------------------
### Задание №1 - Подготовка рабочей среды

Terraform:
![alt text](https://github.com/Sergey81128552/DevOps-homeworks/blob/main/Terraform.jpg "Terraform")
Bash:
![alt text](https://github.com/Sergey81128552/DevOps-homeworks/blob/main/Bash.jpg "Bash")
Markdown:
![alt text](https://github.com/Sergey81128552/DevOps-homeworks/blob/main/Markdown.jpg "Markdown")
Yaml:
![alt text](https://github.com/Sergey81128552/DevOps-homeworks/blob/main/Yaml.jpg "Yaml")
Jsonnet:
![alt text](https://github.com/Sergey81128552/DevOps-homeworks/blob/main/Jsonnet.jpg "Jsonnet")

### Задание №2 - Описание жизненного цикла задачи (разработки нового функционала)
Жизненный цикл программного обеспечения - это промежуток времени от момента принятия решения о создании программного продукта до момента его полного изъятия из эксплуатации.

Жизненный цикл традиционно разделяют на следующие основные этапы:
1. Анализ требований
2. Проектирование
3. Кодирование (программирование)
4. Тестирование и отладка
5. Эксплуатация и сопровождение

2.4. Инструменты Git - Сергей Емельянов
--------------------------------------------

1. $ git show aefea --pretty=oneline --quiet

aefead2207ef7e2aa5dc81a34aedf0cad4c32545

Update CHANGELOG.md
	
2. $ git show 85024d3 --pretty=format:%D --quiet

tag: v0.12.23
	
3. $ git show b8d720 --pretty=format:%P --quiet

56cd7859e05c36c06b56d013b55a252d0bb7e158

9ea88f22fc6269854151c571162c5bcf958bee2b

4. $ git log v0.12.23..v0.12.24 --pretty=oneline

33ff1c03bb960b332be3af2e333462dde88b279e (tag: v0.12.24) v0.12.24

b14b74c4939dcab573326f4e3ee2a62e23e12f89 [Website] vmc provider links

3f235065b9347a758efadc92295b540ee0a5e26e Update CHANGELOG.md

6ae64e247b332925b872447e9ce869657281c2bf registry: Fix panic when server is unreachable

5c619ca1baf2e21a155fcdb4c264cc9e24a2a353 website: Remove links to the getting started guide's old location

06275647e2b53d97d4f0a19a0fec11f6d69820b5 Update CHANGELOG.md

d5f9411f5108260320064349b757f55c09bc4b80 command: Fix bug when using terraform login on Windows

4b6d06cc5dcb78af637bbb19c198faff37a066ed Update CHANGELOG.md

dd01a35078f040ca984cdd349f18d0b67e486c35 Update CHANGELOG.md

225466bc3e5f35baa5d07197bbc079345b77525e Cleanup after v0.12.23 release

5. $ git log -S "func providerSource(" --oneline | tail -n 1

8c928e835 main: Consult local directories as potential mirrors of providers

6. $ git log -S "globalPluginDirs" --oneline

35a058fb3 main: configure credentials from the CLI config file

c0b176109 prevent log output during init

8364383c3 Push plugin discovery down into command package


7. $ git log -S "synchronizedWriters" --pretty=format:%an | tail -n 1

Martin Atkins
