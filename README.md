You type: Buy milk in the input.
You press Enter or tap the button.
The form fires a submit event.
Your handler runs:
preventDefault() → no page reload.
input.value → "Buy milk".
createElement('li') → new li in memory.
li.textContent = "Buy milk" → text inside li.
appendChild(li) → Buy milk shows up as a new list item.
