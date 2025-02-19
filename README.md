# 6000.0.35f1-bug-tmp-bold-italic

Issue tracker: https://issuetracker.unity3d.com/issues/tmp-bold-font-style-is-rendered-with-incorrect-font-when-a-font-asset-without-bold-typeface-is-selected.

Replicated in:
| Version | Status           |
|---------|------------------|
| .26     | :x:              |
| .33     | :x:              |
| .34     | :x:              |
| .35     | :white_check_mark: |
| .36     | :white_check_mark: |
| .38     | :white_check_mark: |

# Screenshots:

## Bold
with bold modifier:
![image](https://github.com/user-attachments/assets/f2245c08-cc70-4cfa-b9b8-3f189c360bac)
without bold modifier:
![image](https://github.com/user-attachments/assets/9ac55f60-79e0-43a2-b5c2-cb824daccafe)

## Italic
with italic modifier:
![image](https://github.com/user-attachments/assets/5aff3279-173d-42f3-8b38-9c5e9504d8f9)
without italic modifier:
![image](https://github.com/user-attachments/assets/f307e124-d694-468e-8e61-e2171de3e00c)

Please note that both bold and italic at the same time will work properly.

Our team suspects this coming from https://issuetracker.unity3d.com/issues/text-is-rendered-with-a-different-font-when-the-fallbackbolditalic-font-is-selected.
