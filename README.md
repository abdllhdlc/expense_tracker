# 💰 Expense Tracker

A beautiful and intuitive expense tracking application built with Flutter. Track your daily expenses, categorize them, and visualize your spending patterns with interactive charts.

![Flutter](https://img.shields.io/badge/Flutter-3.10+-02569B?logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-3.10+-0175C2?logo=dart&logoColor=white)

## ✨ Features

- 📝 **Add Expenses**: Easily add new expenses with title, amount, date, and category
- 🗂️ **Categorization**: Organize expenses into 4 categories:
  - 🍔 Food (Yiyecek)
  - ✈️ Travel (Gezi)
  - 🎬 Entertainment (Keyif)
  - 📚 Work/School (Okul)
- 📊 **Visual Analytics**: Interactive bar chart showing spending distribution across categories
- 🗑️ **Swipe to Delete**: Intuitively remove expenses with swipe gesture
- ↩️ **Undo Functionality**: Restore accidentally deleted expenses
- 📱 **Responsive Design**: Optimized for both mobile and tablet devices
- 🌓 **Theme Support**: Beautiful Material Design 3 with light and dark themes
- ✅ **Form Validation**: Input validation with user-friendly error messages
- 📅 **Date Picker**: Easy date selection for expense entries
- 🎨 **Modern UI**: Clean and modern interface with gradient charts

## 🚀 Getting Started

### Prerequisites

- Flutter SDK (3.10.0 or higher)
- Dart SDK (3.10.0 or higher)
- Android Studio / VS Code with Flutter extensions
- iOS Simulator (for iOS development) or Android Emulator

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/abdllhdlc/expense_tracker.git
   cd expense_tracker
   ```

2. **Install dependencies**
   ```bash
   flutter pub get
   ```

3. **Run the app**
   ```bash
   flutter run
   ```

## 📦 Dependencies

- `flutter`: SDK
- `uuid: ^4.5.1` - Unique ID generation for expenses
- `intl: ^0.20.2` - Date formatting and localization
- `cupertino_icons: ^1.0.8` - iOS-style icons

## 🏗️ Project Structure

```
lib/
├── main.dart                 # App entry point and theme configuration
├── models/
│   └── expense.dart          # Expense model and ExpenseBucket class
└── widgets/
    ├── expenses.dart         # Main expenses screen
    ├── new_expense.dart      # Add expense form
    ├── chart/
    │   ├── chart.dart        # Chart container widget
    │   └── chart_bar.dart    # Individual chart bar widget
    └── expenses_list/
        ├── expenses_list.dart # Expenses list container
        └── expense_item.dart  # Individual expense item widget
```

## 🎯 Key Features Explained

### Expense Management
- Each expense has a unique ID generated using UUID
- Expenses are stored in memory (can be extended with local storage)
- Support for Turkish currency (TL) formatting

### Chart Visualization
- Dynamic bar chart showing relative spending across categories
- Automatically adjusts based on maximum expense value
- Gradient background for visual appeal
- Category icons displayed below each bar

### Responsive Layout
- Mobile (< 600px): Vertical layout with chart on top
- Tablet/Desktop (≥ 600px): Horizontal layout with chart on the left

### Platform Support
- ✅ Android
- ✅ iOS
- ✅ Web
- ✅ Windows
- ✅ macOS
- ✅ Linux

## 🛠️ Technologies Used

- **Flutter** - Cross-platform UI framework
- **Dart** - Programming language
- **Material Design 3** - Design system
- **StatefulWidget** - State management
- **Custom Widgets** - Reusable UI components

## 📝 Usage

1. **Adding an Expense**:
   - Tap the "+" button in the app bar
   - Fill in the title, amount, date, and select a category
   - Tap "Kaydet" (Save) to add the expense

2. **Viewing Expenses**:
   - All expenses are displayed in a scrollable list
   - The chart at the top shows spending distribution

3. **Deleting an Expense**:
   - Swipe left or right on any expense item
   - Use "Geri Al" (Undo) in the snackbar to restore if needed

## 🎨 Theme Configuration

The app supports both light and dark themes with custom color schemes:

- **Light Theme**: Blue-based color scheme
- **Dark Theme**: Dark blue/gray color scheme

You can switch themes by modifying `themeMode` in `main.dart`:
- `ThemeMode.system` - Follows system settings
- `ThemeMode.light` - Always light
- `ThemeMode.dark` - Always dark

## 🔮 Future Enhancements

- [ ] Local database persistence (SQLite/Hive)
- [ ] Export expenses to CSV/PDF
- [ ] Budget setting and tracking
- [ ] Monthly/yearly expense reports
- [ ] Search and filter functionality
- [ ] Multiple currency support
- [ ] Cloud sync
- [ ] Expense statistics and insights

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 👤 Author

**Your Name**
- GitHub: [@abdllhdlc](https://github.com/abdllhdlc)

## 🙏 Acknowledgments

- Flutter team for the amazing framework
- Material Design team for the design system
- All contributors and open-source community

---

⭐ If you like this project, give it a star on GitHub!
