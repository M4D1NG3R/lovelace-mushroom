# Lock card

![Lock light](../images/lock-light.png)
![Lock dark](../images/lock-dark.png)

## Description

A lock card allow you to control a lock entity.

## Configuration variables

All the options are available in the lovelace editor but you can use `yaml` if you want.

| Name                | Type    | Default     | Description                                                               |
| :------------------ | :------ | :---------- | :------------------------------------------------------------------------ |
| `entity`            | string  | Required    | Lock entity                                                               |
| `icon`              | string  | Optional    | Custom icon                                                               |
| `name`              | string  | Optional    | Custom name                                                               |
| `layout`            | string  | Optional    | Layout of the card. Vertical, horizontal and default layout are supported |
| `hide_state`        | boolean | `false`     | Hide the entity state                                                     |
| `tap_action`        | action  | `more-info` | Home assistant action to perform on tap                                   |
| `hold_action`       | action  | `more-info` | Home assistant action to perform on hold                                  |
| `double_tap_action` | action  | `more-info` | Home assistant action to perform on double_tap                            |

## Override theme variables

| Name                             | Type   | Default        | Description                 |
| :------------------------------- | :----- | :------------- | :-------------------------- |
| `--mush-rgb-state-lock-locked`   | string | `--rgb-green`  | Locked state color          |
| `--mush-rgb-state-lock-unlocked` | string | `--rgb-red`    | Unlocked state color        |
| `--mush-rgb-state-lock-pending`  | string | `--rgb-orqnge` | Pending action status color |