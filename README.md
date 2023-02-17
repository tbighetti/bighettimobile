Chart (com.bighetti.Mobile.Chart)

![image](https://user-images.githubusercontent.com/1813123/219675274-7f5b0e06-4f9b-4702-b206-b428603694c6.png)

```csharp
com.bighetti.Mobile.Chart.SerieGroup serieGroup1 = new com.bighetti.Mobile.Chart.SerieGroup();
serieGroup1.Label = "Group 1";
serieGroup1.Series.Add("Item 1", 20);
serieGroup1.Series.Add("Item 2", -40);
serieGroup1.Series.Add("Item 3", 50);

com.bighetti.Mobile.Chart.SerieGroup serieGroup2 = new com.bighetti.Mobile.Chart.SerieGroup();
serieGroup2.Label = "Group 2";
serieGroup2.Series.Add("Item 1", 70);
serieGroup2.Series.Add("Item 2", 90);
serieGroup2.Series.Add("Item 3", -80);

com.bighetti.Mobile.Chart.SerieGroup serieGroup3 = new com.bighetti.Mobile.Chart.SerieGroup();
serieGroup3.Label = "Group 3";
serieGroup3.Series.Add("Item 1", 10);
serieGroup3.Series.Add("Item 2", 30);
serieGroup3.Series.Add("Item 3", 40);

chartBar1.Groups.Add(serieGroup1);
chartBar1.Groups.Add(serieGroup2);
chartBar1.Groups.Add(serieGroup3);

chartBar1.Format = "n0";

chartBar1.Refresh();
```

Controls (com.bighetti.Mobile.Controls)

![image](https://user-images.githubusercontent.com/1813123/219675460-86130bcf-0ab3-4c10-82cb-22d9d931d9e8.png)

```csharp
Keyboard Decimal keyboardNumeric1.TextBox = textBoxDecimal1;
keyboardNumeric1.DecimalSeparator = true;
keyboardNumeric1.Decimals = 2;
```
