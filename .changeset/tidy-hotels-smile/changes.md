Run .resolveInput() on all fields/field hooks regardless of if data has been passed as part of the mutation. This enables .resolveInput() to be run on fields without data during an update mutation.