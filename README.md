# A collection of customizable Nova Fields

## WIP

We are working in a rewrite of every "native" fields that come with Nova.

The idea is make them more configurable and reusable in package development. We have done Text, Number and Boolean so far. If you like the idea you can collaborate with us with your awesome PRs!

Some examples:

```php
Boolean::make('Activo', 'active')
                ->yesLabel('Yeah')
                ->noLabel('Nope')
                ->hideLabelInDetail()
                ->dotClasses('some classes')
                ->successClass('bg-warning')
```

We are also adding events in vue components that propagates up to the chain so the parent notices when something has happened

Looking forward to see your feedback.
