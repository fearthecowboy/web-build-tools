## API Report File for "@microsoft/api-documenter"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

// @public
export interface IApiDocumenterPluginManifest {
    features: IFeatureDefinition[];
    manifestVersion: 1000;
}

// @public
export interface IFeatureDefinition {
    featureName: string;
    kind: 'MarkdownDocumenterFeature';
    subclass: {
        new (initialization: PluginFeatureInitialization): MarkdownDocumenterFeature;
    };
}

// @public
export class MarkdownDocumenterFeature extends PluginFeature {
}

// @public
export abstract class PluginFeature {
    // @internal
    constructor(initialization: PluginFeatureInitialization);
    // @virtual
    onInitialized(): void;
}

// @public
export class PluginFeatureInitialization {
    // @internal
    constructor();
}


// (No @packageDocumentation comment for this package)

```
