EXCLUDES := .DS_Store .git .gitmodules .circleci.yml
TARGET := $(wildcard *.sh)
TARGET_FILES := $(filter-out $(EXCLUDES), ${TARGET})

echo:
	@$(foreach val, $(TARGET_FILES), echo $(abspath $(val)))
