# epa141a-flood-policy-optimization-overijssel

## Background

...

## Project Objectives

...

## Actor Perspective: Analyst of Overijssel Province

...

## Key Model Components

... [add XLMR diagram img]


- **Uncertainties (X)** 

    | **Name** | **Description** | **Potential Impact** |
    |----------|-----------------|----------------------|
    | `discount rate {timestep}` | The percentage used to **discount future damages** to present value. Values: 1.5%, 2.5%, 3.5%, 4.5%. | Affects weight of future losses. Higher rate = less importance given to future damages. |
    | `A.{dike_ring}_ID flood wave shape` | Index for one of 133 **predefined flood wave hydrographs** (lookup data). | Different flood timing and peak level influences severity of flood damage differently. |
    | `A.{dike_ring}_Bmax` | **Maximum breach width** (30–350 m). | Larger Bmax = more water outflow, wider inundation, higher damages and casualties. |
    | `A.{dike_ring}_pfail` | **Probability of dike failure**, from 0 to 1. | Higher `pfail` increases risk of breach and subsequent flooding. |
    | `A.{dike_ring}_Brate` | **Breach growth rate** in m/day. Typical values: 0, 1.5, or 10. | Higher `Brate` = faster flood propagation, less time for response or evacuation. |

- **Levers (L)**

    | **Name** | **Description** | **Potential Impact** |
    |----------|-----------------|----------------------|
    | `A.{dike_ring}_DikeIncrease {planning_step}` | Height increase (0–10 decimeters) for a specific dike ring `{dike_ring}` at a given planning step `{planning_step}` | Reduces flood probability in targeted area; increases cost and may affect land use |
    | `{project_id}_RfR {planning_step}` | Implementation decision (0 = no, 1 = yes) for a Room for the River project `{project_id}` at step `{planning_step}` | Enhances flow capacity and ecological value; affects land and budget use |
    | `EWS_DaysToThreat` | Number of days (0–4) of early warning before expected flooding, system-wide | More time for evacuation; lowers casualties; critical under fast breach conditions |

- **Outcomes Metrices (M)**

    The outcome metrices can be collected as aggregated outcomes (summation of outcomes across all locations) and disaggragated outcomes (outcomes associated to each dike ring locations).

    | **Name** | **Description** | **Aggregation Level** |
    |----------|-----------------|-----------------------|
    | Total Costs | Total of all cost types | Aggregated/Disaggregated |
    | Expected Number of Deaths | Total deaths across all dikes | Aggregated/Disaggregated |
    | Expected Annual Damage | Total or per-dike annual flood damage | Aggregated/Disaggregated |
    | Dike Investment Costs | Total or per-dike investment costs | Aggregated/Disaggregated |
    | RfR Investment Costs | Total Room for the River project costs | Aggregated |
    | Evacuation Costs | Total evacuation costs | Aggregated |

## Analysis Methods

...

## Results

...

## Policy Recommendations

...





## Model Origin
This project is for academic use under TU Delft’s EPA141A (2025). This project builds upon the original model available at [https://github.com/quaquel/epa141A_open](https://github.com/quaquel/epa141A_open)

## Authors
Myriam Kammüller Pont, Rachel Delvin Sutiono, Thunchanok Phutthaphaiboon, Yao Wang | TU Delft – Engineering & Policy Analysis