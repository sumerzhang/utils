## API Report File for "@silence_zhpf/utils"

> Do not edit this file. It is a report generated by [API Extractor](https://api-extractor.com/).

```ts

// @public
export class Area {
    add(other: Area): Area;
    static new(value: number, unit?: Unit): Area;
    sub(other: Area): Area;
    toString(): string;
    // (undocumented)
    readonly unit: Unit;
    // (undocumented)
    readonly value: number;
}

// @public
export function calcBirthday(no: string): string;

// @public
export function calcSex(no: string): "男" | "女";

// @public
export class Distance {
    add(other: Distance): Distance;

    div(factor: number): Distance;

    format({precision, unit}: Format): string;

    mul(factor: number): Distance;
    static new(value: number, unit?: DistanceUnit): Distance;
    sub(other: Distance): Distance;
    toCm(): Distance;
    toDm(): Distance;
    toKm(): Distance;
    toM(): Distance;
    toMm(): Distance;

    toString(): string;

    // (undocumented)
    readonly unit: DistanceUnit;
    // (undocumented)
    readonly value: number;
}

// @public
export type DistanceUnit = "mm" | "cm" | "dm" | "m" | "km";

// @public
export interface Format {
    // (undocumented)
    precision?: number;
    // (undocumented)
    unit?: boolean;
}

// @public
export function isEven(n: number): boolean;

// @public
export function isFalse(value: any): boolean;

// @public
export function isOdd(n: number): boolean;

// @public
export function isTrue(value: any): boolean;

// @public
export type Unit = "mm2" | "cm2" | "dm2" | "m2" | "km2";

// @public
export function verity(no: string): boolean;

// @public
export function whenFalse(fn: () => void): (a: any) => any;

// @public
export function whenTrue(fn: () => void): (a: any) => any;

// (No @packageDocumentation comment for this package)

```
