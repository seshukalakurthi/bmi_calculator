# BMI Calculator

Simple ASP.NET Core Razor Pages BMI calculator that accepts imperial inputs (stones/pounds and feet/inches), calculates BMI, and shows the BMI category.

## Project Structure

- `/home/runner/work/bmi_calculator/bmi_calculator/bmi2021` - Web app project (`net9.0`)
- `/home/runner/work/bmi_calculator/bmi_calculator/BMILabtestproject` - MSTest unit tests (`net9.0`)
- `/home/runner/work/bmi_calculator/bmi_calculator/bmi2025.sln` - Solution file

## Prerequisites

- .NET SDK 9.0+

## Run Locally

From repository root (`/home/runner/work/bmi_calculator/bmi_calculator`):

```bash
dotnet restore
dotnet run --project /home/runner/work/bmi_calculator/bmi_calculator/bmi2021/bmi2025.csproj
```

Open the URL shown in the console. The BMI page is configured as the landing page (`/`).

## Run Tests

From repository root:

```bash
dotnet test /home/runner/work/bmi_calculator/bmi_calculator/BMILabtestproject/BMILabtestproject.csproj
```

## CI

GitHub Actions workflow:

- Builds the solution
- Runs unit tests
- Publishes app artifacts
