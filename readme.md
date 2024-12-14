<p align="center">
    <img src="https://raw.githubusercontent.com/PKief/vscode-material-icon-theme/ec559a9f6bfd399b82bb44393651661b08aaf7ba/icons/kotlin.svg" align="center" width="20%">
</p>
<p align="center"><h1 align="center">NLW KOTLIN NEARBY</h1></p>
<p align="center">
	<img src="https://img.shields.io/github/last-commit/maycon8609/nlw-kotlin-nearby?style=default&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/maycon8609/nlw-kotlin-nearby?style=default&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/maycon8609/nlw-kotlin-nearby?style=default&color=0080ff" alt="repo-language-count">
</p>

<p align="center">
	<img src="https://img.shields.io/badge/kotlin-030712?style=for-the-badge&logo=kotlin" alt="kotlin badge">
	<img src="https://img.shields.io/badge/typescript-030712?style=for-the-badge&logo=typescript" alt="typescript badge">
</p>

<p align="center">
	<!-- default option, no dependency badges. -->
</p>
<br>

## Table of Contents

- [ Overview](#overview)
- [ Features](#features)
- [ Project Structure](#project-structure)
  - [ Project Index](#project-index)
- [ Contributing](#contributing)

---

## Overview

**nlw kotlin nearby** is an open-source project designed for coupon management. Built with Kotlin, it provides users with a seamless experience to discover nearby markets, access coupons, and scan QR codes for discounts. Ideal for tech enthusiasts and developers interested in enhancing user interactions.

---

## Features

|     |     Feature      | Summary                                                                                                                                                                                                 |
| :-- | :--------------: | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| ⚙️  | **Architecture** | <ul><li>Uses TypeScript for backend services</li><li>Utilizes Kotlin for frontend components</li></ul>                                                                                                  |
| 🔩  | **Code Quality** | <ul><li>Consistent coding style across Kotlin and TypeScript</li><li>Linting and code formatting tools integrated</li></ul>                                                                             |
| 🔌  | **Integrations** | <ul><li>Uses Prisma for database integration</li><li>Integrates with external APIs for location services</li></ul>                                                                                      |
| 🧩  |  **Modularity**  | <ul><li>Modular backend services with clear boundaries</li><li>Separation of concerns in frontend components</li><li>Reusable components and libraries</li></ul>                                        |
| ⚡️ | **Performance**  | <ul><li>Optimized backend services for fast response times</li><li>Efficient frontend rendering for smooth user experience</li><li>Caching strategies implemented for performance improvement</li></ul> |
| 📦  | **Dependencies** | <ul><li>Uses Gradle for Kotlin dependencies management</li><li>Uses npm for TypeScript dependencies management</li><li>Dependency versions locked for stability</li></ul>                               |

---

## Project Structure

```sh
└── nlw-kotlin-nearby/
    ├── api
    │   ├── .env
    │   ├── .gitignore
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── prisma
    │   ├── src
    │   └── tsconfig.json
    ├── app
    │   ├── .gitignore
    │   ├── build.gradle.kts
    │   ├── proguard-rules.pro
    │   └── src
    ├── build.gradle.kts
    ├── gradle
    │   ├── libs.versions.toml
    │   └── wrapper
    ├── gradle.properties
    ├── gradlew
    ├── gradlew.bat
    └── settings.gradle.kts
```

### Project Index

<details open>
	<summary><b><code>NLW-KOTLIN-NEARBY/</code></b></summary>
	<details> <!-- __root__ Submodule -->
		<summary><b>__root__</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/gradlew.bat'>gradlew.bat</a></b></td>
				<td>- Facilitates Gradle execution by setting up JVM options and locating the Java executable<br>- Resolves the Gradle wrapper's classpath and initiates Gradle execution with specified options<br>- Handles JAVA_HOME validation and provides error messages for invalid configurations<br>- Maintains script integrity and ensures proper execution flow for Windows environments.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/settings.gradle.kts'>settings.gradle.kts</a></b></td>
				<td>- Manages plugin and dependency repositories for the project, ensuring access to essential libraries and tools<br>- Facilitates efficient resolution of dependencies and plugin management, enhancing the project's build process.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/build.gradle.kts'>build.gradle.kts</a></b></td>
				<td>Manages common configuration options for all sub-projects/modules in the codebase, controlling the application, Kotlin, and Compose compiler plugins.</td>
			</tr>
			</table>
		</blockquote>
	</details>
	<details> <!-- api Submodule -->
		<summary><b>api</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/tsconfig.json'>tsconfig.json</a></b></td>
				<td>- Configures TypeScript compiler options for the API module to ensure strict type checking and compatibility with ES2022 and ES2023 standards<br>- Maps custom paths for module resolution and enforces consistent file naming conventions.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/package.json'>package.json</a></b></td>
				<td>Define the API configuration for the Nearby App, specifying dependencies, scripts, and version details.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/package-lock.json'>package-lock.json</a></b></td>
				<td>- The `api/package-lock.json` file in the project structure manages dependencies for the API module<br>- It ensures that the necessary packages like "@prisma/client", "express", and "zod" are locked to specific versions for consistent and reliable functionality<br>- This file plays a crucial role in maintaining the stability and integrity of the API module within the codebase architecture.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/.env'>.env</a></b></td>
				<td>Enables configuration of the database URL for the API within the project structure.</td>
			</tr>
			</table>
			<details>
				<summary><b>src</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/server.ts'>server.ts</a></b></td>
						<td>- The code in `api/src/server.ts` sets up an Express server to handle incoming requests, define routes, and manage errors<br>- It listens on a specified port and logs a message upon successful startup<br>- This file plays a crucial role in initializing the server and routing requests within the project architecture.</td>
					</tr>
					</table>
					<details>
						<summary><b>middlewares</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/middlewares/error-handling.ts'>error-handling.ts</a></b></td>
								<td>- Handles errors in the API by returning appropriate responses based on the type of error encountered<br>- It distinguishes between application errors and validation errors, providing specific messages and status codes accordingly<br>- This middleware ensures consistent error handling throughout the project, enhancing the overall reliability and user experience.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>utils</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/utils/AppError.ts'>AppError.ts</a></b></td>
								<td>Defines a reusable class for handling custom error messages and status codes within the API.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>controllers</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/controllers/markets-controller.ts'>markets-controller.ts</a></b></td>
								<td>- The MarketsController in the api/src/controllers/markets-controller.ts file handles requests related to market data<br>- It retrieves markets based on category or specific IDs and returns the results in a structured format<br>- This controller plays a crucial role in managing market-related operations within the project's architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/controllers/categories-controller.ts'>categories-controller.ts</a></b></td>
								<td>- The CategoriesController in the api/src/controllers/categories-controller.ts file retrieves and returns a list of categories in ascending order from the database<br>- This controller plays a crucial role in handling requests related to categories within the project's architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/controllers/coupons-controller.ts'>coupons-controller.ts</a></b></td>
								<td>- The CouponsController in the api/src/controllers/coupons-controller.ts file handles coupon updates for a specific market in the project<br>- It validates parameters, decrements available coupons, generates a unique coupon code, and returns it in the response<br>- This controller ensures proper management of coupons for the market entities in the system.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>routes</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/routes/categories-route.ts'>categories-route.ts</a></b></td>
								<td>Defines routes for categories using Express Router and connects them to the Categories Controller for handling category-related requests in the API.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/routes/coupons-route.ts'>coupons-route.ts</a></b></td>
								<td>- Defines API routes for updating coupons in the system, utilizing the CouponsController to handle requests<br>- The file plays a crucial role in structuring the project's backend architecture by facilitating communication between the client and server for coupon-related operations.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/routes/index.ts'>index.ts</a></b></td>
								<td>- Defines routes for categories, markets, and coupons using Express Router in the API<br>- Organizes and delegates requests to corresponding route handlers<br>- Facilitates structured navigation and separation of concerns within the codebase architecture.</td>
							</tr>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/routes/markets-route.ts'>markets-route.ts</a></b></td>
								<td>- Defines routes for market data retrieval based on category and ID, utilizing the MarketsController to handle requests<br>- This file plays a crucial role in structuring the API endpoints for accessing market information within the project architecture.</td>
							</tr>
							</table>
						</blockquote>
					</details>
					<details>
						<summary><b>database</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/src/database/prisma.ts'>prisma.ts</a></b></td>
								<td>Enables database connectivity and query logging using PrismaClient in the project's API module.</td>
							</tr>
							</table>
						</blockquote>
					</details>
				</blockquote>
			</details>
			<details>
				<summary><b>prisma</b></summary>
				<blockquote>
					<table>
					<tr>
						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/prisma/seed.ts'>seed.ts</a></b></td>
						<td>- The `seed.ts` file in the `api/prisma` directory is responsible for seeding initial data into the database tables for categories and markets<br>- It populates the database with predefined categories like "Alimentação," "Compras," "Hospedagem," "Cinema," and "Padaria." This seeding process ensures that the application starts with essential data for these entities, setting up a foundation for further operations within the codebase architecture.</td>
					</tr>
					<tr>
						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/prisma/schema.prisma'>schema.prisma</a></b></td>
						<td>- Defines data models and relationships for categories, markets, and rules in the Prisma schema<br>- Establishes how categories, markets, and rules are structured and connected, facilitating efficient data management and retrieval.</td>
					</tr>
					</table>
					<details>
						<summary><b>migrations</b></summary>
						<blockquote>
							<table>
							<tr>
								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/prisma/migrations/migration_lock.toml'>migration_lock.toml</a></b></td>
								<td>Ensure version control system tracks the SQLite provider for Prisma migrations in the specified file path.</td>
							</tr>
							</table>
							<details>
								<summary><b>20241112181659_create_tables</b></summary>
								<blockquote>
									<table>
									<tr>
										<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/api/prisma/migrations/20241112181659_create_tables/migration.sql'>migration.sql</a></b></td>
										<td>- Defines database schema for categories, rules, and markets with necessary constraints<br>- Establishes relationships between markets and categories, and rules and markets<br>- Crucial for maintaining data integrity and organizing information in the database.</td>
									</tr>
									</table>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<details> <!-- app Submodule -->
		<summary><b>app</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/build.gradle.kts'>build.gradle.kts</a></b></td>
				<td>- Configure Android application settings, dependencies, and build features<br>- Set up namespaces, SDK versions, and ProGuard rules<br>- Include libraries for maps, Coil, navigation, serialization, ZXing, and more<br>- Enable Compose features and exclude specific resources during packaging<br>- Implement testing dependencies for JUnit and Espresso.</td>
			</tr>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/proguard-rules.pro'>proguard-rules.pro</a></b></td>
				<td>- Defines project-specific ProGuard rules to optimize and secure the Android app during the build process<br>- Controls configuration files applied in the build.gradle<br>- Enables preserving line number information for debugging stack traces and hiding original source file names<br>- Essential for enhancing app performance and protecting code integrity.</td>
			</tr>
			</table>
			<details>
				<summary><b>src</b></summary>
				<blockquote>
					<details>
						<summary><b>main</b></summary>
						<blockquote>
							<details>
								<summary><b>java</b></summary>
								<blockquote>
									<details>
										<summary><b>com</b></summary>
										<blockquote>
											<details>
												<summary><b>rocketseat</b></summary>
												<blockquote>
													<details>
														<summary><b>nlw</b></summary>
														<blockquote>
															<details>
																<summary><b>nearby</b></summary>
																<blockquote>
																	<table>
																	<tr>
																		<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/MainActivity.kt'>MainActivity.kt</a></b></td>
																		<td>- The MainActivity orchestrates navigation and screen transitions within the app, connecting various UI screens like Splash, Welcome, Home, Market Details, and QR Code Scanner<br>- It leverages Jetpack Compose and ViewModel to manage UI state and events, providing a seamless user experience flow through the different sections of the application.</td>
																	</tr>
																	</table>
																	<details>
																		<summary><b>ui</b></summary>
																		<blockquote>
																			<details>
																				<summary><b>route</b></summary>
																				<blockquote>
																					<table>
																					<tr>
																						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/route/UIRoutes.kt'>UIRoutes.kt</a></b></td>
																						<td>- Define UI routes for different screens in the app using Kotlin serialization for seamless data handling<br>- The file declares objects representing screens like Splash, Welcome, Home, and QRCodeScanner, enhancing navigation and data transfer within the app architecture.</td>
																					</tr>
																					</table>
																				</blockquote>
																			</details>
																			<details>
																				<summary><b>screen</b></summary>
																				<blockquote>
																					<details>
																						<summary><b>home</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/home/HomeScreen.kt'>HomeScreen.kt</a></b></td>
																								<td>- Defines the HomeScreen function responsible for rendering the main UI layout<br>- It integrates components like NearbyMarketCardList and NearbyGoogleMap to display markets and categories<br>- Utilizes BottomSheetScaffold for a cohesive user experience, with dynamic content based on user interactions.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/home/HomeUiState.kt'>HomeUiState.kt</a></b></td>
																								<td>Defines the UI state for the home screen, encapsulating categories, markets, and market locations.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/home/HomeViewModel.kt'>HomeViewModel.kt</a></b></td>
																								<td>Manages UI state and data fetching for categories and markets in the Home screen using coroutines and LiveData.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/home/HomeUiEvent.kt'>HomeUiEvent.kt</a></b></td>
																								<td>Define UI events for the Home screen to handle category and market fetching.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>qrcode_scanner</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/qrcode_scanner/QRCodeScannerScreen.kt'>QRCodeScannerScreen.kt</a></b></td>
																								<td>- Enables QR code scanning functionality for the app's coupon feature, handling camera permissions and launching the barcode scanner<br>- The screen prompts users to scan a QR code, processing the result for further actions.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>welcome</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/welcome/WelcomeScreen.kt'>WelcomeScreen.kt</a></b></td>
																								<td>- Defines the WelcomeScreen UI component responsible for displaying a welcome screen with header, content, and a button to navigate to the home screen<br>- The component is composed using Jetpack Compose, providing a visually appealing and interactive user experience.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>market_details</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/market_details/MarketDetailsUiEvent.kt'>MarketDetailsUiEvent.kt</a></b></td>
																								<td>- Defines UI events for market details screen, including fetching rules and coupons, and resetting coupons<br>- This file encapsulates user interactions specific to market details, enhancing modularity and clarity in the codebase architecture.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/market_details/MarketDetailsUiState.kt'>MarketDetailsUiState.kt</a></b></td>
																								<td>Define the UI state for market details, including rules and coupons.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/market_details/MarketDetailsScreen.kt'>MarketDetailsScreen.kt</a></b></td>
																								<td>- The MarketDetailsScreen code file in the project's architecture displays detailed information about a market, including its image, name, description, rules, and coupons<br>- It also allows users to navigate to a QR code scanner<br>- This screen provides a visually appealing and informative layout for users to interact with market details seamlessly.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/market_details/MarketDetailsViewModel.kt'>MarketDetailsViewModel.kt</a></b></td>
																								<td>- Manages market details UI state by fetching coupons and rules from a remote data source<br>- Updates UI state based on successful or failed fetch operations<br>- Provides functionality to reset the coupon state<br>- Facilitates seamless interaction between UI events and data retrieval processes.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>splash</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/screen/splash/SplashScreen.kt'>SplashScreen.kt</a></b></td>
																								<td>- Define the splash screen UI for the app, displaying a logo and background image<br>- Delays navigation to the welcome screen for 3 seconds upon launch.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																				</blockquote>
																			</details>
																			<details>
																				<summary><b>util</b></summary>
																				<blockquote>
																					<table>
																					<tr>
																						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/util/MapUtils.kt'>MapUtils.kt</a></b></td>
																						<td>Calculate the southwest and northeast points based on a list of coordinates for map rendering.</td>
																					</tr>
																					</table>
																				</blockquote>
																			</details>
																			<details>
																				<summary><b>theme</b></summary>
																				<blockquote>
																					<table>
																					<tr>
																						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/theme/Type.kt'>Type.kt</a></b></td>
																						<td>- Define typography styles for the project using the Rubik font family, with varying weights and sizes<br>- The code in the provided file sets up text styles for different elements like headlines, titles, body text, and labels, ensuring a consistent visual design across the application.</td>
																					</tr>
																					<tr>
																						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/theme/Theme.kt'>Theme.kt</a></b></td>
																						<td>- Define the color scheme and typography for the app's theme, allowing for easy customization of light and dark modes<br>- The `NearbyTheme` function sets the appropriate colors based on the selected theme, ensuring a consistent visual experience across the application.</td>
																					</tr>
																					<tr>
																						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/theme/Color.kt'>Color.kt</a></b></td>
																						<td>- Define a color palette for the UI theme, including shades of green, red, and gray<br>- The file establishes specific color values to maintain consistency and visual appeal throughout the project's user interface.</td>
																					</tr>
																					</table>
																				</blockquote>
																			</details>
																			<details>
																				<summary><b>component</b></summary>
																				<blockquote>
																					<details>
																						<summary><b>button</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/button/NearbyButton.kt'>NearbyButton.kt</a></b></td>
																								<td>- Defines a reusable Composable function for a custom button component in the UI, allowing customization of text, icon, and click behavior<br>- The button's appearance and behavior are configured based on input parameters, promoting consistency and flexibility across the app's user interface.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>home</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/home/NearbyGoogleMap.kt'>NearbyGoogleMap.kt</a></b></td>
																								<td>- Generates a dynamic Google Map displaying user and market locations with custom markers<br>- Animates the camera to focus on all locations for an enhanced user experience.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>market</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/market/NearbyMarketCardList.kt'>NearbyMarketCardList.kt</a></b></td>
																								<td>- Generates a Composable list of nearby markets for display in the UI, facilitating user exploration of local venues<br>- The list is populated with market data and supports interaction through market selection<br>- This component enhances the user experience by providing a visually appealing and interactive way to discover nearby locations.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/market/NearbyMarketCard.kt'>NearbyMarketCard.kt</a></b></td>
																								<td>- Define a Composable function for displaying market details, including name, description, and available coupons<br>- Utilizes a Card layout with image, text, and icon components<br>- Enables interaction via onClick callback<br>- Designed to showcase market information in a visually appealing and structured manner.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>category</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/category/CategoryFilterChipView.kt'>CategoryFilterChipView.kt</a></b></td>
																								<td>- Define category filter chip views with descriptions and icons for various categories in the app<br>- Includes a method to retrieve a category based on its description<br>- This file centralizes the configuration of category filter chip views, enhancing maintainability and consistency in the app's UI components.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/category/NearbyCategoryFilterChipList.kt'>NearbyCategoryFilterChipList.kt</a></b></td>
																								<td>- Enables selection of category filters in a Compose UI list, triggering a callback when a category is chosen<br>- The list displays filter chips horizontally, allowing users to toggle between categories<br>- The selected category is highlighted, updating dynamically based on user interaction.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/category/NearbyCategoryFilterChip.kt'>NearbyCategoryFilterChip.kt</a></b></td>
																								<td>- Defines a Composable function for a filter chip component that displays category information<br>- Handles category selection and styling based on user interaction.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>welcome</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/welcome/WelcomeHowItWorksTip.kt'>WelcomeHowItWorksTip.kt</a></b></td>
																								<td>- Define a reusable Composable function for displaying a welcome tip with an icon, title, and subtitle in the UI component<br>- This function enhances the user onboarding experience by visually presenting key information.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/welcome/WelcomeHeader.kt'>WelcomeHeader.kt</a></b></td>
																								<td>- Defines a Composable function for the WelcomeHeader component, displaying the Nearby App logo and welcoming message with promotional content<br>- The function organizes the layout using Jetpack Compose elements for a visually appealing user interface.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/welcome/WelcomeContent.kt'>WelcomeContent.kt</a></b></td>
																								<td>- Defines a Composable function to render a welcome screen with information on how the app works<br>- Displays tips on finding nearby locations, using QR codes for discounts, and accessing benefits from various establishments<br>- Organized in a column layout with spaced elements for clear presentation.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																					<details>
																						<summary><b>market_details</b></summary>
																						<blockquote>
																							<table>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/market_details/NearbyMarketDetailsCoupons.kt'>NearbyMarketDetailsCoupons.kt</a></b></td>
																								<td>- Defines a Composable function for displaying coupons in the market details screen<br>- It arranges coupons in a visually appealing manner with icons and text<br>- The function takes a list of coupons and renders them with specific styling<br>- This component enhances the user experience by showcasing available discounts effectively.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/market_details/NearbyMarketDetailsRules.kt'>NearbyMarketDetailsRules.kt</a></b></td>
																								<td>- Define and display market rules in a visually appealing format for a nearby market details screen<br>- The code file structures and presents rules with appropriate styling and spacing, enhancing user experience.</td>
																							</tr>
																							<tr>
																								<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/ui/component/market_details/NearbyMarketDetailsInfos.kt'>NearbyMarketDetailsInfos.kt</a></b></td>
																								<td>- Define and structure UI components for displaying market details, including coupons, address, and phone number<br>- Utilizes Jetpack Compose for building the UI layout<br>- Composable function renders the information with specified styles and icons<br>- Preview function showcases the component with mock data.</td>
																							</tr>
																							</table>
																						</blockquote>
																					</details>
																				</blockquote>
																			</details>
																		</blockquote>
																	</details>
																	<details>
																		<summary><b>core</b></summary>
																		<blockquote>
																			<details>
																				<summary><b>network</b></summary>
																				<blockquote>
																					<table>
																					<tr>
																						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/core/network/KtorHttpClient.kt'>KtorHttpClient.kt</a></b></td>
																						<td>- Manages HTTP client configuration for Android using Ktor, including timeout settings, content negotiation, and logging<br>- Facilitates network communication with defined JSON serialization settings and logging levels.</td>
																					</tr>
																					<tr>
																						<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/main/java/com/rocketseat/nlw/nearby/core/network/NearbyRemoteDataSource.kt'>NearbyRemoteDataSource.kt</a></b></td>
																						<td>- Handles network requests to fetch categories, markets, market details, and generate coupons based on QR code scans<br>- Utilizes Ktor HTTP client to interact with the backend API endpoints<br>- The code in this file serves as the data source for retrieving and processing information related to nearby markets and coupons.</td>
																					</tr>
																					</table>
																				</blockquote>
																			</details>
																		</blockquote>
																	</details>
																</blockquote>
															</details>
														</blockquote>
													</details>
												</blockquote>
											</details>
										</blockquote>
									</details>
								</blockquote>
							</details>
						</blockquote>
					</details>
					<details>
						<summary><b>test</b></summary>
						<blockquote>
							<details>
								<summary><b>java</b></summary>
								<blockquote>
									<details>
										<summary><b>com</b></summary>
										<blockquote>
											<details>
												<summary><b>rocketseat</b></summary>
												<blockquote>
													<details>
														<summary><b>nlw</b></summary>
														<blockquote>
															<details>
																<summary><b>nearby</b></summary>
																<blockquote>
																	<table>
																	<tr>
																		<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/test/java/com/rocketseat/nlw/nearby/ExampleUnitTest.kt'>ExampleUnitTest.kt</a></b></td>
																		<td>Verifies correctness of addition operation in a local unit test for the Rocketseat NLW Nearby project.</td>
																	</tr>
																	</table>
																</blockquote>
															</details>
														</blockquote>
													</details>
												</blockquote>
											</details>
											<details>
												<summary><b>example</b></summary>
												<blockquote>
													<details>
														<summary><b>nearby</b></summary>
														<blockquote>
															<table>
															<tr>
																<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/test/java/com/example/nearby/ExampleUnitTest.kt'>ExampleUnitTest.kt</a></b></td>
																<td>Verifies correctness of addition operation in the nearby project's unit test.</td>
															</tr>
															</table>
														</blockquote>
													</details>
												</blockquote>
											</details>
										</blockquote>
									</details>
								</blockquote>
							</details>
						</blockquote>
					</details>
					<details>
						<summary><b>androidTest</b></summary>
						<blockquote>
							<details>
								<summary><b>java</b></summary>
								<blockquote>
									<details>
										<summary><b>com</b></summary>
										<blockquote>
											<details>
												<summary><b>rocketseat</b></summary>
												<blockquote>
													<details>
														<summary><b>nlw</b></summary>
														<blockquote>
															<details>
																<summary><b>nearby</b></summary>
																<blockquote>
																	<table>
																	<tr>
																		<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/androidTest/java/com/rocketseat/nlw/nearby/ExampleInstrumentedTest.kt'>ExampleInstrumentedTest.kt</a></b></td>
																		<td>- Verifies the app context on an Android device by running an instrumented test<br>- This test ensures that the correct package name is associated with the app under test<br>- The code is located in the ExampleInstrumentedTest.kt file within the app/src/androidTest/java/com/rocketseat/nlw/nearby directory of the project structure.</td>
																	</tr>
																	</table>
																</blockquote>
															</details>
														</blockquote>
													</details>
												</blockquote>
											</details>
											<details>
												<summary><b>example</b></summary>
												<blockquote>
													<details>
														<summary><b>nearby</b></summary>
														<blockquote>
															<table>
															<tr>
																<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/app/src/androidTest/java/com/example/nearby/ExampleInstrumentedTest.kt'>ExampleInstrumentedTest.kt</a></b></td>
																<td>- Verifies the app context on an Android device by running an instrumented test<br>- This test ensures that the correct package name is associated with the app under test<br>- The code is part of the Android test suite and contributes to the overall quality assurance of the project.</td>
															</tr>
															</table>
														</blockquote>
													</details>
												</blockquote>
											</details>
										</blockquote>
									</details>
								</blockquote>
							</details>
						</blockquote>
					</details>
				</blockquote>
			</details>
		</blockquote>
	</details>
	<details> <!-- gradle Submodule -->
		<summary><b>gradle</b></summary>
		<blockquote>
			<table>
			<tr>
				<td><b><a href='https://github.com/maycon8609/nlw-kotlin-nearby/blob/master/gradle/libs.versions.toml'>libs.versions.toml</a></b></td>
				<td>Manages library versions and dependencies for the project, ensuring compatibility and consistency across modules.</td>
			</tr>
			</table>
		</blockquote>
	</details>
</details>

---

### Prerequisites

Before getting started with nlw-kotlin-nearby, ensure your runtime environment meets the following requirements:

- **Programming Language:** Kotlin
- **Package Manager:** Gradle, Npm
- **Container Runtime:** Docker

## Contributing

- **💬 [Join the Discussions](https://github.com/maycon8609/nlw-kotlin-nearby/discussions)**: Share your insights, provide feedback, or ask questions.
- **🐛 [Report Issues](https://github.com/maycon8609/nlw-kotlin-nearby/issues)**: Submit bugs found or log feature requests for the `nlw-kotlin-nearby` project.
- **💡 [Submit Pull Requests](https://github.com/maycon8609/nlw-kotlin-nearby/blob/main/CONTRIBUTING.md)**: Review open PRs, and submit your own PRs.

<details closed>
<summary>Contributing Guidelines</summary>

1. **Fork the Repository**: Start by forking the project repository to your github account.
2. **Clone Locally**: Clone the forked repository to your local machine using a git client.
   ```sh
   git clone https://github.com/maycon8609/nlw-kotlin-nearby
   ```
3. **Create a New Branch**: Always work on a new branch, giving it a descriptive name.
   ```sh
   git checkout -b new-feature-x
   ```
4. **Make Your Changes**: Develop and test your changes locally.
5. **Commit Your Changes**: Commit with a clear message describing your updates.
   ```sh
   git commit -m 'Implemented new feature x.'
   ```
6. **Push to github**: Push the changes to your forked repository.
   ```sh
   git push origin new-feature-x
   ```
7. **Submit a Pull Request**: Create a PR against the original project repository. Clearly describe the changes and their motivations.
8. **Review**: Once your PR is reviewed and approved, it will be merged into the main branch. Congratulations on your contribution!
</details>

<details closed>
<summary>Contributor Graph</summary>
<br>
<p align="left">
   <a href="https://github.com{/maycon8609/nlw-kotlin-nearby/}graphs/contributors">
      <img src="https://contrib.rocks/image?repo=maycon8609/nlw-kotlin-nearby">
   </a>
</p>
</details>

---
