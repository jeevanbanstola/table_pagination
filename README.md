<!--
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages).

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages).
-->

DESCRIPTION: A Flutter package that provides a table pagination widget for easy navigation between pages.


# Table Pagination

A Flutter package that provides a table pagination widget for easy navigation between pages.

## Installation

Add the following to your `pubspec.yaml` file:

```yaml
dependencies:
  table_pagination: ^1.0.0
## Usage

EXAMPLE:
TablePagination(
  handleIndexChange: (int pageIndex) {
    // Handle index change logic here
      },
  pageIndex: 1, // Initial page index
  totalRows: 100, // Total number of rows in the table
  limit: 10, // Number of rows per page
  kcPrimaryColor: Colors.blue, // Customize the primary color
)


CONTRIBUTION: Contributions are welcome! If you find a bug or want to add a new feature, please open an issue or submit a pull request.

LISENCE: 
Please note that the structure and content of your `README.md` may vary based on the features and documentation you want to provide for your `table_pagination` package. Customize it according to your specific package details.
