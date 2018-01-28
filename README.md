# react-native-birthday-picker

React Native DatePicker with an optional year.
Good for birthdays where sometimes you only know the month/day.

***Usage***

```javascript
import BirthdayPicker from './BirthdayPicker';

<BirthdayPicker
  yearsBack={50}
  yearsForward={0}
  onYearValueChange={(year,i) => console.log("Year was changed to: ", year)}
  onMonthValueChange={(month,i) => console.log("Month was changed to: ", month)}
  onDayValueChange={(day,i) => console.log("Day was changed to: ", day)}
/>
```
