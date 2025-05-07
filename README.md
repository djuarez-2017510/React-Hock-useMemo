# Character search with useMemo

This project is an optimized search application that allows you to filter characters by name or description.

## Functionality

- Search for characters within a list.
- Adds new characters with name and description.
- Search is case sensitive.
- Uses `useMemo` to avoid unnecessary filters in each rendering.

## Goal of the exercise

Demonstrate the use of `useMemo` to memorize results of heavy computations (in this case, user filtering). The filter result is only recalculated if the users or the search text changes.

## Technologies

- React
- JSX (via Babel)
- useMemo

Translated with DeepL.com (free version)