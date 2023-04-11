# Liberating Structures

Online meetings are difficult for a variety of reasons. It can be hard to engage participants. It can be difficult to participate. There is a delay that often results in participants speaking over one another. With any sufficiently large online meeting, it gets difficult to make progress collaboratively towards an objective. To address the challenges inherent in big group online meetings, we experiment with techniques:

1. we make smaller meetings
2. we take turns explicitly
3. we vote and talk about things in order of popularity
4. we have someone who facilitates the meeting to ensure we have the right outcomes and action items

These techniques are better than nothing, but they have limitations too:

1. when you make smaller meetings, you may leave someone important out of the discussion
2. taking explicit turns adds a lot of wait time for those who aren't speaking, and they may not have interest in the topic but not feel strongly enough to interrupt
3. sometimes the most useful conversations are not the most popularity
4. sometimes the person who cares enough to facilitate is someone who ought to contribute as well but can't manage both facilitation and participation at the same time

## Liberating structures are useful for online meetings

Liberating structures are a series of techniques that make it easier for large groups to generate effective outcomes by virtue of a repeatable simple set of processes that require limited top-down facilitation. This is incredibly powerful for online meetings in particular, since those online meetings make it even more difficult for everyone to participate equally. However, these techniques are difficult to use with only breakout rooms since breakout rooms alone are too basic a primitive block to automate this process. Using breakouts, someone still needs to manage creation and assigning of the breakout rooms. This slack bot intends to automate the processes needed to facilitate using liberating structures so that you don't need to do so by hand. Currently the bot supports two of these, chosen for their simplicity of implementation as well as their utility:

### 1-2-4-all

This structure breaks up an arbitrarily sized group into pairs, then foursomes, and puts everyone back together again. By breaking out into smaller groups it optimizes for everyone to have a contribution and a chance to think about the topic(s) at hand. Progressively combining the groups ensures that the feedback will make it back to the larger group. Afterwards, there is a slack thread available for asynchronous conversation to continue.

### impromptu networking

This structure takes a group of people and pairs them up to discuss a prompt, switching pairs every 5 minutes. It is a nice icebreaker to enable everyone to participate and get to know each other.

## Sources

This bot aims to replicate the liberating structures defined [here](https://www.liberatingstructures.com/) in slack using forms, threads, huddles, etc to enable serendipitous synchronous conversations in slack.
