
> flutter create --org com.zaw consumer
> flutter run

-------------------------------------------------------

export 'utils/export_utils.dart';
export 'network/export_network.dart';

-------------------------------------------------------

dependencies:
  flutter:
    sdk: flutter
  shared:
    path: ../shared

-------------------------------------------------------

flutter run --dart-define=CONFIG_THEME_COLOR=COLOR_FOOD_PANDA --dart-define=CONFIG_APP_TITLE=APP_TITLE_FOOD_PANDA