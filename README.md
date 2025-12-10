# Mealke

![Mealke Logo](assets/Mealke%20Banner.png)

<p align="center">
  <a href="https://apps.apple.com/br/app/mealke/id6742419813?l=en-GB
Mealke">
    <img src="https://toolbox.marketingtools.apple.com/api/v2/badges/download-on-the-app-store/black/en-us?releaseDate=1759881600"
         alt="Download on the App Store"
         style="width: 245px; height: 62px; object-fit: contain;" />
  </a>
</p>

🇧🇷 [PT-BR Version](https://github.com/educcamara/Mealke/tree/pt-br)

## About


<p align="center">
  <a href="https://www.wwdcscholars.com/s/421F4CAF-7383-43DC-8278-114633C05473/2025">
    <img src="assets/SSC-Winner_enUS.png"
         alt="WWDC 2025 Swift Student Challenge Winner"
         style="width: auto; height: 150px; object-fit: contain;"
	/>
  </a>
</p>

One of my greatest passions is cooking, preparing meal preps, and making good use of the ingredients I have on the shelf. Over time, I realized that keeping my inventory organized, planning meals consistently, and especially avoiding food waste was becoming a challenge.

That’s when the idea to create **Mealke** came up, an app designed to help me manage ingredients, structure my meals, and reduce waste. It works as a simple hub where you can register each item with its expiration date while simultaneously planning and tracking meal preparation.

**Main features:**

Food Storage Tracking:
- Register pantry, fridge, or freezer items to keep track of what’s available
- Assign expiration dates to items and avoid waste
- View stored items organized by categories
- Track multiple batches of the same food with different expiration dates or quantities

Meal Tracking:
- Plan meals by selecting ingredients and recording the quantities used
- Register meal preparation to know what was cooked and stored in each location
- Record breakfast, lunch, dinner, or snacks at any time
- Track which ingredients were used in each meal
- Keep a clear history of your consumption with a weekly meal overview

## Technologies and Things

- App built with Swift
- Frontend modeled in SwiftUI
- Local data persistence with SwiftData
- TipKit for introducing features in the app
- GitFlow + Conventional Commits in the Git workflow
- Unit tests with XCTest for schema migration in SwiftData

### MVVM in SwiftUI

Application of the **MVVM** pattern in the front-end layer with SwiftUI, separating Views from business logic and ensuring that each screen is guided by a clear ViewModel with well-defined states and effects.

### SwiftData for Local Persistence

Creation of an entity that contains the configurations and context of SwiftData tables, with generic CRUD operations to make data manipulation easier.

In addition, the schema setup was done using `VersionedSchemas`, allowing safe schema migration for production versions.

### TipKit for Features

Implementation of **TipKit** to introduce features within the app, guiding users through contextual tips that improve the experience and help with feature discovery.

### Unit Tests with XCTest

Development of unit tests using the **XCTest** framework to ensure the integrity of schema migration operations in SwiftData, guaranteeing that data is preserved correctly during app updates.