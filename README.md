<figure>
<img src="./assets/images/AMQ-Cursors-HighLevel.png"
alt="AMQ-Cursors-HighLevel" />
</figure>

# What are Message Cursors?

<figure>
<img src="./assets/images/AMQ-Cursors-HighLevelCursors.png"
alt="AMQ-Cursors-HighLevelCursors" />
</figure>

<figure>
<img src="./assets/images/AMQ-Cursors-GenericCursor.png"
alt="AMQ-Cursors-GenericCursor" />
</figure>

## Types of Message Cursors

Store-based cursors are used by default to handle persistent messages.

VM cursors are very fast, but cannot handle slow message consumers.

File-based cursors are used by default to handle non-persistent
messages. They are useful when the message store is slow and message
consumers are relatively fast.

### Store Cursor

<figure>
<img src="./assets/images/AMQ-Cursors-Fast-Store.png"
alt="AMQ-Cursors-Fast-Store" />
</figure>

<figure>
<img src="./assets/images/AMQ-Cursors-Slow-Store.png"
alt="AMQ-Cursors-Slow-Store" />
</figure>

### VM Cursor

<figure>
<img src="./assets/images/AMQ-Cursors-VM.png" alt="AMQ-Cursors-VM" />
</figure>

### File Based Cursor

<figure>
<img src="./assets/images/AMQ-Cursors-FileBased.png"
alt="AMQ-Cursors-FileBased" />
</figure>

# Conclusion
