
# GGF_spider_controle

checking and deleting xml files from spider folder that are old
Sends email to rpa_team 

### Process triggers

Every two hours (currently disabled)

### Jira LInk

- [NA]()

### subject matter expert

- [NA](Email)

## Input 

#### Dependencies


| Dependencies | Version     |
| :-------- | :------- |
| `ggf_library` | `1.0.13` | 
| `UiPath.System.Activities` | `19.10.1` | 
|`UiPath.Excel.Activities`|`2.7.2`|
|`UiPath.Mail.Activities`|`19.10.1`|
|`UiPath.UIAutomation.Activities`|`19.10.1`|



#### Assets input

| Assets |
|:-----| 
|`rpa_team`|


### applications input

NA


### Queue Names input

| queue names | in    |
NA


## Output

#### Queue items output

|queue item name| Output|
|:--------------|:------|
|`internal_ails_q`| `email with check spider folder of certain proccess` |

### Files output

|file including extension| Output|
|:--------------|:------|
NA
### Assets output

NA


## Exceptions

### Business exceptoins


### Process keywords

