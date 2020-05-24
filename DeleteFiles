import os

dir_name = "C:/Users/catha/Downloads"
test = os.listdir(dir_name)


def deleteFiles():
    userPrint = "Enter following commands to delete file types:\nppt(x)\nzip\nrar\nexe\ndoc(x)\n"
    userInput = input(userPrint + "\n")
    if userInput == "ppt":
        for item in test:
            if item.endswith(".pptx") or item.endswith(".ppt"):
                os.remove(os.path.join(dir_name, item))
    elif userInput == "zip":
        for item in test:
            if item.endswith(".zip"):
                os.remove(os.path.join(dir_name, item))

    elif userInput == "rar":
        for item in test:
            if item.endswith(".rar"):
                os.remove(os.path.join(dir_name, item))

    elif userInput == "exe":
        for item in test:
            if item.endswith(".exe"):
                os.remove(os.path.join(dir_name, item))

    elif userInput == "docx":
        for item in test:
            if item.endswith(".docx") or item.endswith(".doc"):
                os.remove(os.path.join(dir_name, item))

    else:
        print("Incorrect Input")
        deleteFiles()


deleteFiles()
