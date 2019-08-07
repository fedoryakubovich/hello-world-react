# React Salute &middot; [![GitHub license](https://img.shields.io/badge/license-MIT-blue.svg)](https://github.com/fedoryakubovich/react-salute/blob/master/LICENSE) [![npm version](https://img.shields.io/npm/v/react-salute.svg?style=flat)](https://www.npmjs.com/package/react-salute) [![Build Status](https://travis-ci.com/fedoryakubovich/react-salute.svg?branch=master)](https://travis-ci.org/) [![Coverage Status](https://coveralls.io/repos/github/fedoryakubovich/react-salute/badge.svg?branch=master)](https://coveralls.io/github/fedoryakubovich/react-salute?branch=master)

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Documentation](#documentation)
- [Examples](#examples)

## Installation

`npm install react-salute`

## Usage

```javascript
import React from 'react';
import ReactSalute from 'react-salute';

const ReactSaluteExamples = () => {
  return (
    <section>
      <ReactSalute />
      <ReactSalute name="Foo" />
    </section>
  );
};

export default ReactSaluteExamples;
```

## Documentation

| Name | Description                    | Type   | Default |
| :--- | :----------------------------- | :----- | :------ |
| name | Name of the one who is saluted | String | 'React' |

## Examples

You can see live examples of the react-salute package [here](https://react-salute.herokuapp.com/).
