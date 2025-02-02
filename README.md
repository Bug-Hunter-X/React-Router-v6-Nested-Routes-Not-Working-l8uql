# React Router v6 Nested Routes Issue

This repository demonstrates a common issue encountered when working with nested routes in React Router v6. The problem arises from an incorrect nesting structure that prevents the nested component from rendering properly.

## Problem Description
The provided code uses nested routes to render different components based on the URL. However, only the parent component is rendered, even though navigation to the nested path occurs.

## Solution
The solution involves fixing the route structure in the application's routing configuration.  The nested route should be placed correctly within its parent route to ensure that the nested component is able to render.