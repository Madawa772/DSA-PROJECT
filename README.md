Group members:
Tulela Kamati 224030043
Ze Figura 224077015
Vinzen Nangolo 223078980
Madawa !Nou-Gawaseb 224009435
Gerson Hishono 224032550

Pseudocodes:

1. Insert Contact:
   	Function insertContact(phonebook, contactName, contactNumber)
    // Check if phonebook is full
    IF phonebook is full THEN
        PRINT "Phonebook is full!"
        RETURN
    END IF

    // Insert the new contact
    contact = {name: contactName, number: contactNumber}
    ADD contact to phonebook
    PRINT "Contact inserted successfully!"
END Function

2.Search Contact:
Function searchContact(phonebook, contactName)
    FOR each contact in phonebook DO
        IF contact.name == contactName THEN
            PRINT "Contact Found: ", contact.name, contact.number
            RETURN contact
        END IF
    END FOR
    PRINT "Contact not found!"
END Function

3. Display All Contacts:
Function displayContacts(phonebook)
    IF phonebook is empty THEN
        PRINT "Phonebook is empty!"
        RETURN
    END IF

    FOR each contact in phonebook DO
        PRINT "Name: ", contact.name, "Number: ", contact.number
    END FOR
END Function

4. Delete Contact:
Function deleteContact(phonebook, contactName)
    FOR each contact in phonebook DO
        IF contact.name == contactName THEN
            REMOVE contact from phonebook
            PRINT "Contact deleted successfully!"
            RETURN
        END IF
    END FOR
    PRINT "Contact not found!"
END Function

5. Update Contact:
Function updateContact(phonebook, contactName, newNumber)
    FOR each contact in phonebook DO
        IF contact.name == contactName THEN
            contact.number = newNumber
            PRINT "Contact updated successfully!"
            RETURN
        END IF
    END FOR
    PRINT "Contact not found!"
END Function


