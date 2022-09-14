using Random

function number_guess_computer()

    print("Please enter a number between 1 and 50 for the computer to try and guess: ")
    
    number = parse(Int64, readline())
    guess_order = collect(1:50)
    rng = MersenneTwister(1234)
    shuffled = shuffle(rng, guess_order)
    for guess in shuffled

        if guess == number
            print("\nThe computer cracked the code and guessed it right!")
            break 
        end
        
        print("\nComputer guessed: $guess")
    end
end

number_guess_computer()
