# Four Kitchens Drupal Recipes Cookoff

Welcome to the Four Kitchens Drupal Recipes Cookoff, where we're blending the world of coding with the excitement of a culinary competition! While there's no actual food involved, we're cooking up something special in the Drupal community. We introduce you to a cutting-edge concept: ~Recipes~. Just like a great chef follows a recipe to create a delightful dish, our engineers are creating Recipes to organize and share code for Drupal features and configurations.

## What Are Drupal Recipes?

Recipes are a remarkable way to structure and package code, making it easier to add new features to your website. Just as a well-crafted recipe guides you through the process of creating a delicious meal, a Drupal Recipe helps you set up a new feature or configuration on your website. It's all about making your Drupal experience tastier, simpler, and more efficient.

## Join the Drupal Recipes Cookoff

We invite you to participate in the Cookoff and submit your own Drupal Recipes in one of the following categories:

1. Appetizers: Start small by submitting a basic module setup or a set of essential configurations. For example, you can create Recipes for date or WYSIWYG formatters, or set up the Gin theme and admin toolbar.

2. Entrees: Go big with fully formed Recipes representing complete website features. This could include Recipes for an image gallery, events calendar, alerts banner, content types, SEO settings, and more. Showcase your Drupal culinary skills with a full course!

3. Dessert: Get playful and creative with Recipes that are fun, silly, or even a bit unconventional. Show us how versatile Recipes can be by creating something as unique as an easter egg, just for the fun of learning.

## Why Join?

* **Hands-on Experience**: Gain practical experience with the latest technology in the Drupal world. Recipes are the future, and this is your chance to get ahead of the curve.

* **Sales Potential**: As we create valuable Recipes for different marketing verticals, you'll have the chance to explore new sales opportunities for your skills and expertise.

* **Open Source Contribution**: Embrace the spirit of open source by sharing your Recipes with the community. Your contributions can help others while establishing your reputation as a leader in the Drupal space.

* **Community Leadership**: Take the initiative to lead and inspire others in the Drupal community. Sharing your knowledge and experience can have a positive ripple effect.

## How to Get Started

```bash
# Clone this repo. It contains relevant patches and example recipes.
git clone https://github.com/fourkitchens/recipe-cookoff

# Install a site from the existing configuration as a common starting place.
lando start
lando composer install
lando drush si --existing-config

# See a recipe in action.
cd web
lando php core/scripts/drupal recipe recipes/custom/blaster
lando drush cr

# Optional: Recipes are not modules; so you may want to unpack the dependencies.
composer unpack njim/blaster
```

## Useful Resources and Docs

* [Distributions and Recipes initiative](https://www.drupal.org/project/distributions_recipes)
* [Initiative documentation](https://git.drupalcode.org/project/distributions_recipes/-/blob/1.0.x/docs/recipe.md)
* [Dupal recipe cookbook](https://www.drupal.org/docs/extending-drupal/contributed-modules/contributed-module-documentation/distributions-and-recipes-initiative/recipes-cookbook)
* [Getting started article](https://www.velir.com/ideas/2023/05/03/exploring-the-new-recipes-feature-in-drupal-10)
* [Drupal #distributions-and-recipes slack channel](https://drupal.slack.com/archives/C2THUBAVA)
