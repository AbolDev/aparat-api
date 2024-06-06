### Errors

#### `IncorrectPasswordError(Exception)`
Exception raised for incorrect password errors.

#### `LoginFailedError(Exception)`
Exception raised for login failed errors.

#### `UsernameNotFoundError(Exception)`
Exception raised for username not found errors.

#### `LoginRequiredError(Exception)`
Exception raised for login required errors.

#### `VideoNotFoundError(Exception)`
Exception raised for video not found errors.

#### `ResolutionError(Exception)`
Exception raised when the specified video resolution is unavailable.

### Enums

#### `ReportReason(Enum)`
Enumeration for reasons to report a video.

- `FAKE_NEWS = 45`
- `NATIONAL_SECURITY = 24`
- `IMPROPER_CLOTHING = 25`
- `SEXUAL_CONTENT = 26`
- `ETHNIC_INSULTS = 27`
- `RELIGIOUS_INSULTS = 28`
- `POLITICAL_INSULTS = 29`
- `VIOLENT_CONTENT = 30`
- `DEFAMATION = 31`
- `DANGEROUS_ACTIVITIES = 32`
- `HATE_SPEECH = 33`
- `CHILD_ABUSE = 34`
- `INAPPROPRIATE_FOR_CHILDREN = 35`
- `IMITATIVE_BEHAVIOR = 36`
- `MISLEADING_CONTENT = 37`
- `VIOLATION_OF_RULES = 38`
- `MISLEADING_TITLE = 39`
- `PRIVACY_VIOLATION = 40`
- `COPYRIGHT_VIOLATION = 41`
- `UNAUTHORIZED_ADVERTISING = 42`
- `TECHNICAL_PROBLEM = 43`
- `OTHER = 44`

#### `VideoCategory(Enum)`
Enumeration for video categories.

- `VIDEO_GAME = 22`
- `SPORTS = 11`
- `CARTOON_ANIMATION = 18`
- `COMEDY = 2`
- `EDUCATION = 3`
- `ENTERTAINMENT = 4`
- `MOVIE_SERIES_DOCUMENTARY = 5`
- `RELIGION = 6`
- `MUSIC = 7`
- `NEWS = 8`
- `LAW_POLITICS = 9`
- `TECHNOLOGY_COMPUTER = 10`
- `TRAVEL_TOURISM = 13`
- `ANIMALS = 14`
- `BUSINESS = 16`
- `CULTURE_ART = 17`
- `FASHION_STYLE = 20`
- `HEALTH = 21`
- `FOOD_DRINK = 23`
- `AUTOMOTIVE = 24`
- `FAMILY_CHILD = 25`
- `HOME_LIFE = 26`
- `ENVIRONMENT = 27`
- `FINANCE_ECONOMY = 28`
- `SOCIAL = 29`
- `BASIC_SCIENCES = 30`
- `AGRICULTURE_HORTICULTURE = 31`