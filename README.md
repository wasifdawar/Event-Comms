# Salesforce DX Project: Communicate from Child to Parent

Explore different approaches to communicating between Lightning web components.

## Communicate from Child to Parent

Build Lightning web components that communicate with one another.
Communicate from a child component to its parent component.
Communicate from a parent component to a child component.
Communicate from a component to an unrelated component.

## Communicate from Parent to Child

To enable communication from a parent component to a child component, the child exposes a property or function to make it public. Then the parent can update the child's public property or call the child's public function.

## Communicate Between Unrelated Components

To communicate across the subtrees in the DOM (and under some circumstances between different browser windows logged into the same org), use Lightning message service (LMS). LMS is a publish and subscribe service that facilitates communication between Lightning web components, Aura components, and Visualforce pages.  

Use LMS for communication between unrelated components unless you control both components and a common parent. LMS is powerful, effective, and easy to use, but don’t let that tempt you to use it when it’s not necessary. Firing DOM events is much more efficient. When you need to communicate between components with a parent that you can’t control, such as two App Builder slots, Lightning message service is the perfect choice.

- [Salesforce Trailhead Module Link](https://trailhead.salesforce.com/content/learn/projects/communicate-between-lightning-web-components?trailmix_creator_id=journeytosalesforce&trailmix_slug=all-about-lwc)

## Wasif's TrailHead Profile Link

- [Wasif Dawar Trailhead Profile Link](https://www.salesforce.com/trailblazer/wasifdawar16)
