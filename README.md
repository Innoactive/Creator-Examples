# Innoactive Creator Examples

This repository is a showcase for the [Innoactive Creator](https://github.com/Innoactive/Creator) and its components. It includes every supported component, an example of a template, and examples for designers in separate scenes.

## Getting Started

Refer to our [Getting Started](http://developers.innoactive.de/documentation/creator/latest/articles/getting-started/index.html) guide.

As a developer, you might want to clone this repository instead of importing the Unity package. Given that you have launched Git BASH inside the folder you want to have this Unity project, first clone the repository:

```
git clone git@github.com:Innoactive/XR-Creator-Examples.git
```

and go into the Assets folder of the Unity project.

```
cd XR-Creator-Examples/Assets
```

### [Creator Core](https://github.com/Innoactive/Creator)

Every project in this list depends on the Creator Core. It contains fundamental definitions, generally applicable logic, and the visual editor.

```
git submodule add git@github.com:Innoactive/Creator.git Innoactive/Creator/Core
```

### [Basic Conditions and Behaviors Component](https://github.com/Innoactive/Basic-Conditions-And-Behaviors)

This component contains very simple conditions and behaviors that involve no interaction with trainees. For example, a condition on a timer, or a behavior that moves its target object. 

```
git submodule add git@github.com:Innoactive/Basic-Conditions-And-Behaviors.git Innoactive/Creator/Components/Basic-Conditions-And-Behaviors-Component
```

### [Basic Interaction Component](https://github.com/Innoactive/Basic-Interaction-Component)

This component is an abstraction layer between the Creator Core and a component that would implement user interactions.

```
git submodule add git@github.com:Innoactive/Basic-Interaction-Component.git Innoactive/Creator/Components/Basic-Interaction 
```

### [Unity XR Interaction Component](https://github.com/Innoactive/XR-Interaction-Component)

This component implements user interactions in VR by using the Unity XR framework. Include the Basic Interaction component along this repository to your project to let designers create training applications for VR.

```
git submodule add git@github.com:Innoactive/XR-Interaction-Component.git Innoactive/Creator/Components/XR-Interaction-Component
```

### [Text-To-Speech Component](https://github.com/Innoactive/TextToSpeech-Component)

This component uses text-to-speech engines so designers could generate audio instructions for trainees.

```
git submodule add git@github.com:Innoactive/TextToSpeech-Component.git Innoactive/Creator/Components/TextToSpeech-Component
```

### [Base Template](https://github.com/Innoactive/Creator-Base-Template)

This template makes an initial setup of the Creator, and serves both as example and as a starting point for creating new templates. Every VR training application project includes one template.

```
git submodule add git@github.com:Innoactive/Creator-Base-Template.git Innoactive/Creator/Base-Template
```

## Documentation

Start with [this page](http://developers.innoactive.de/documentation/creator/latest/articles/getting-started/index.html) and then proceed with our [developer's guide](http://developers.innoactive.de/documentation/creator/latest/articles/developer/index.html). This way you will get familiar with our tool and will know how to configure and extend it.

An overview of the example courses provided can be found [here](http://developers.innoactive.de/documentation/creator/v2.0.0/articles/innoactive-creator/examples.html).

## Contributing

See our [contributor's guide](.github/CONTRIBUTING.md).

## Maintainers

You can find contacts of current maintainers in the [Maintainers](.github/CONTRIBUTING.md#maintainers) section of our contributing guidelines.

## License

This repository is licensed under the Apache License, Version 2.0. See the [LICENSE](LICENSE) file for the full text.

## Acknowledgements

We have referenced every 3rd party work we use in this repository in the [NOTICE](NOTICE) file.

We list all contributors to this repository in the [Contributors](.github/CONTRIBUTING.md#contributors) section of our contributing guidelines.
