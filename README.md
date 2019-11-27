# 4-Android-MyResponsiveApplication
The responsive Drunken Poet app.

Key points to consider:
  - In order to make your constraint layout scrollable, it must be wrapped into a ScrollView.
  - To force the size of the constraint layout (increase height) for any case in which the height of your mobile phone device is not enough for your design. Use the attribute minHeight, assign a value let's say 1000dp and you will se how the constraint layout height resizes.
  - The usage of guidelines help to align components you place on the screen. In this example we placed 2 vertical guidelines, for the left and right sides, each at 3% of distance from the screen border. To do it, use the attribute app:layout_constraintGuide_percent and set the value as 0.03 ( as decimal value ), by doing this, no matter the size of the screen the distance between the border of your layout and the guideline will always be 3% of the whole distance( in our case horizontal distance).
  

Components used:
  - ScrollView
  - ConstraintLayout
  - ImageView
  - TextView
  - Guideline
  - Barrier
  - Button
  - ImageButton
  - RatingBar
  
## Example  
![TheDrunkenPoet](https://user-images.githubusercontent.com/4823319/69683588-71368e00-1109-11ea-847d-f0da15ae481c.gif)

## Portrait image. we have added a barrier
![Screenshot_1574814629](https://user-images.githubusercontent.com/4823319/69683593-7b588c80-1109-11ea-95f9-69dab7de5442.png)

## Landscape image. we have added a barrier
![Screenshot_1574814644](https://user-images.githubusercontent.com/4823319/69683594-7bf12300-1109-11ea-98d5-eb5cb4af6709.png)


