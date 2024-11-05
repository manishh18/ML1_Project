# Football Player Dataset

## Overview
This dataset contains detailed information about various football players.The data can be used for various analysis tasks, including player performance evaluation, team building, and statistical modeling.

## Dataset Description
The dataset includes the following attributes:
1. Basic Player Information
 - ID: A unique identifier for each player.
 - Name: The player's name.
 - Age: The player's age.
 - Photo: URL link to the player's photo.
 - Nationality: The country the player represents internationally.
 - Flag: URL link to the flag of the player's nationality.
 - Overall: The player's overall rating (out of 100).
 - Potential: The player's potential rating, representing how good the player could become.
 - Club: The current club the player is playing for.
 - Club Logo: URL link to the club's logo.
 - Value: The estimated market value of the player (in Euros).
 - Wage: The player's weekly wage (in Euros).
 - Special: A score for how "special" or unique the player is within the game.
2. Player Attributes
 - Preferred Foot: Whether the player prefers using their right or left foot.
 - International Reputation: A score (usually 1-5) indicating how well-known the player is globally.
 - Weak Foot: A score (1-5) indicating the player's ability with their non-preferred foot.
 - Skill Moves: A score (1-5) representing the player's ability to perform skill moves.
 - Work Rate: Describes the player’s effort both offensively and defensively, often listed as two categories (e.g., "High/Medium").
 - Body Type: A description of the player's body build.
 - Real Face: Whether the player’s in-game model resembles their real-world appearance ("Yes" or "No").
 - Position: The player’s main position(s) on the field.
 - Jersey Number: The number the player wears on their jersey.
 - Joined: The date the player joined their current club.
 - Loaned From: If the player is on loan, this field shows the player's parent club.
 - Contract Valid Until: The year the player’s contract expires.
 - Height: The player’s height (in feet and inches).
 - Weight: The player’s weight (in pounds).
3. Skill Attributes
These fields represent specific in-game football skills, typically rated from 0 to 100:

 - Crossing: Ability to deliver accurate crosses from the wings.
 - Finishing: Ability to score goals.
 - HeadingAccuracy: Accuracy in heading the ball.
 - ShortPassing: Ability to pass the ball over short distances.
 - Volleys: Ability to strike the ball on the volley.
 - Dribbling: Skill in controlling the ball while dribbling.
 - Curve: Ability to bend the ball, typically for shots and crosses.
 - FKAccuracy: Free-kick accuracy.
 - LongPassing: Ability to pass the ball over long distances.
 - BallControl: Skill in controlling the ball under pressure.
4. Physical Attributes
 - Acceleration: How quickly the player can reach top speed.
 - SprintSpeed: Top speed the player can achieve.
 - Agility: How quickly the player can change direction.
 - Reactions: How quickly the player reacts to situations on the pitch.
 - Balance: The player’s ability to maintain balance.
 - ShotPower: The power behind the player’s shots.
 - Jumping: How high the player can jump.
 - Stamina: How long the player can maintain high levels of performance.
 - Strength: The player’s physical strength in duels.
 - LongShots: Ability to shoot accurately from long distances.
5. Defensive Attributes
 - Aggression: The player’s intensity in challenges and duels.
 - Interceptions: Ability to intercept passes.
 - Positioning: Ability to find and maintain good attacking positions.
 - Vision: Ability to pick out creative passes.
 - Penalties: Skill in taking penalty kicks.
 - Composure: How composed the player is under pressure.
 - Marking: Ability to mark and track opposing players.
 - StandingTackle: Skill in performing standing tackles.
 - SlidingTackle: Skill in performing sliding tackles.
 - GKDiving: Diving ability.
 - GKHandling: Ability to hold onto or catch the ball.
 - GKKicking: Kicking ability.
 - GKPositioning: How well-positioned the goalkeeper is.
 - GKReflexes: Reflexes in goalkeeping situations.
7. Best Position and Rating
 - Best Position: The player’s best position on the field.
 - Best Overall Rating: The best overall rating the player can achieve in their best position.

## Usage
This dataset is ideal for:

- **Performance Analysis:** Evaluate player performance metrics and compare across different attributes.
- **Team Building:** Analyze player attributes to assist in building or optimizing football teams.
- **Statistical Modeling:** Develop predictive models based on player statistics and career information.

## Data Cleaning and Preprocessing
Before using the dataset, consider the following preprocessing steps:

- **Handling Missing Values:** Check for and handle any missing values in the dataset.
- **Standardization:** Standardize numerical values and categories where necessary.
- **Feature Engineering:** Create new features if required for specific analyses or models.


## Models Used
- **Linear Regression**
- **K-Nearest Neighbors Regressor**
- **Random Forest Regressor**

## Evaluation Metrics
- **Mean Squared Error (MSE)**
- **Mean Absolute Error (MAE)**
- **Root Mean Squared Error (RMSE)**
- **R² Score**

## Dependencies
- Python 3.x
- Pandas
- NumPy
- Matplotlib (for visualization)
- Seaborn (for visualization)
- SKlearn (for model)

