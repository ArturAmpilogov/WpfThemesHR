## HOW TO USE IT

Watch small tutorial video http://www.youtube.com/watch?v=U61_0CpTBTo

1. Add theme project to your solution
2. Paste code in App.xaml:

```
        <ResourceDictionary>
            <ResourceDictionary.MergedDictionaries>
                <!-- Reference main style dictionary-->
                <ResourceDictionary Source="pack://application:,,,/HR.Themes.Fischer.WPF;component/Style.xaml"/>
                <!-- Reference color style -->
                <ResourceDictionary Source="pack://application:,,,/HR.Themes.Fischer.WPF;component/Colors/Colors_Blue.xaml"/>
            </ResourceDictionary.MergedDictionaries>
        </ResourceDictionary>
```

Initially the project was crated at High Robotics LTD.