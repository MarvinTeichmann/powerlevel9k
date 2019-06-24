# Virtualenv

![](segment.png)

## Installation

To use this segment, you need to activate it by adding `virtualenv` to your
`P9K_LEFT_PROMPT_ELEMENTS` or `P9K_RIGHT_PROMPT_ELEMENTS` array, depending
where you want to show this segment.

## Configuration

| Variable | Default Value | Description |
|----------|---------------|-------------|
|`P9K_VIRTUALENV_LEFT_DELIMITER`|"("|The left delimiter just before the environment name.|
|`P9K_VIRTUALENV_RIGHT_DELIMITER`|")"|The right delimiter just after the environment name.|

### Color Customization

You can change the foreground and background color of this segment by setting
```
P9K_VIRTUALENV_FOREGROUND='red'
P9K_VIRTUALENV_BACKGROUND='blue'
```

### Customize Icon

The main Icon can be changed by setting `P9K_VIRTUALENV_ICON="my_icon"`. To change the
icon color only, set `P9K_VIRTUALENV_ICON_COLOR="red"`.