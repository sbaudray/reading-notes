# Domain Driven Design (DDD)

Design over technology.

Code is knowledge.

The core domain requires the most attention.

## Event Storming

## Acceptance tests

Given (state), When (actions), Then (results). The domain code is isolated, thus testable without talking to the external world.

## Unit tests

## Bounded contexts

A subdivision of the domain which groups related functionalities under a main concept. One team per bounded context. One repo per bounded context.

## Core Domain

The main bounded context, the one driving your business.

## Ubiquitous language

Each component of the domain has a definition within its bounded context. Definitions do not cross boundaries. Everyone speaks the same language inside a bounded context.

## Entity

An individual thing distinguishable thanks to its identity (id).

## Value object

An immutable object without identity (id) that encapsulates a value.

## Aggregate

A tree of entities and value objects, where the root entity is called the aggregate root.

## Context Mapping

A bridge between two bounded contexts. 

### Partnership

Both teams own a context. They share dependent goals.

### Shared kernel

Part of the contexts is shared between two teams.

### Customer-Supplier

One context has responsibility, but listens to the other's needs.

### Conformist

One context has responsibility, the other must follow.

### Anticorruption Layer

One context translates the foreign ubiquitous language to its own.

### Open host service

An API.

### Published Language

Data format served by the open host service.


## Domain Events
