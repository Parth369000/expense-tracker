# Expense Tracker

A simple, cross-platform expense tracking app built with Flutter. This application allows users to add, view, and categorize their expenses, and visualize spending patterns with charts.

## Features

- **Add Expenses:** Input expense title, amount, date, and select a category (Food, Travel, Leisure, Work).
- **Expense List:** View all added expenses in a scrollable list. Swipe to delete with undo support.
- **Expense Categories:** Expenses are grouped into categories for better organization.
- **Charts:** Visualize your spending by category with a dynamic bar chart.
- **Responsive UI:** Adapts layout for mobile and larger screens.
- **Dark & Light Theme:** Supports both dark and light modes.
- **Platform Adaptation:** Uses Material and Cupertino widgets for Android and iOS look & feel.

## Getting Started

### Prerequisites
- [Flutter SDK](https://flutter.dev/docs/get-started/install)
- Dart 3.5.4 or higher

### Installation
1. **Clone the repository:**
   ```sh
   [git clone <your-repo-url>](https://github.com/Parth369000/expense-tracker.git)
   cd EXPENSE_TRACKER
   ```
2. **Install dependencies:**
   ```sh
   flutter pub get
   ```
3. **Run the app:**
   ```sh
   flutter run
   ```

## Project Structure
- `lib/main.dart` - App entry point, theme setup, and home screen.
- `lib/models/expense.dart` - Expense model and category definitions.
- `lib/widgets/expenses.dart` - Main screen with expense list and chart.
- `lib/widgets/new_expense.dart` - Form to add a new expense.
- `lib/widgets/chart/` - Chart and chart bar widgets for visualization.
- `lib/widgets/expenses_list/` - Expense list and item widgets.

## Dependencies
- [flutter](https://pub.dev/packages/flutter)
- [cupertino_icons](https://pub.dev/packages/cupertino_icons)
- [uuid](https://pub.dev/packages/uuid)
- [intl](https://pub.dev/packages/intl)

## Linting & Code Quality
- Uses [flutter_lints](https://pub.dev/packages/flutter_lints) for recommended best practices.

## License

This project is for learning and demonstration purposes.
